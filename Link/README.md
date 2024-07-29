```markdown
# HTML Examples

This repository contains examples of HTML code demonstrating the use of absolute and relative links, bookmarks, and navigating to bookmarks on another webpage.

## Table of Contents

- [Absolute and Relative Links](#absolute-and-relative-links)
- [Bookmarks](#bookmarks)
- [Navigating to Bookmarks on Another Page](#navigating-to-bookmarks-on-another-page)

## Absolute and Relative Links

File: `link.html`

This file provides examples of absolute and relative URLs.

### Absolute URLs

These are complete URLs that point to a specific location on the web, including the protocol (http or https).

Example:

```html
<a href="https://www.instagram.com/nazmihakimz?igsh=Y2IxMnhieGg4ZzR1" target="_blank">Instagram Nazmi Hakim</a>
```

### Relative URLs

These URLs are relative to the current page. They do not include the protocol or domain name.

Example:

```html
<a href="here/hello.html">hello.html</a>
```

## Bookmarks

File: `bookmark.html`

This file explains how to create bookmarks within the same webpage. Bookmarks allow you to link to specific sections of a page.

Example:

```html
<li><a href="#title1">Title 1</a></li>
```

You can create a bookmark target using the `id` attribute.

Example:

```html
<h1 id="title1">Title 1</h1>
```

## Navigating to Bookmarks on Another Page

File: `bookmark2.html`

This file demonstrates how to create links that navigate to bookmarks on another page.

Example:

```html
<li><a href="bookmark.html#title1">Title 1</a></li>
```

## Usage

Open each HTML file in a web browser to see the examples in action.
