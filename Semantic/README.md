```markdown
# Semantic HTML Example

This document provides an example of using semantic HTML elements to create a well-structured web page. Semantic HTML refers to the use of HTML tags that convey the meaning and structure of the content within them. These tags help improve the accessibility and search engine optimization (SEO) of the web page.

## HTML Structure

Below is the HTML structure of the example web page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic</title>
</head>
<body>
    <header>
        <h1>Page Title</h1>
    </header>
    <nav>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Article</a></li>
            <li><a href="">Our Contact</a></li>
        </ul>
    </nav>
    <section>
        <article>
            <h1>Studying HTML</h1>
            <p>HTML Subject</p>
        </article>
        <article>
            <h1>Studying CSS</h1>
            <p>CSS Subject</p>
        </article>
    </section>
    <footer>
        <p>Powered by Nazmi Hakim <time datetime="2024">2024</time></p>
    </footer>
</body>
</html>
```

## Semantic Elements Used

1. **`<header>`**: Defines the introductory content or a set of navigational links for the web page. In this example, it contains the main title of the page.
    ```html
    <header>
        <h1>Page Title</h1>
    </header>
    ```

2. **`<nav>`**: Represents a section of the page intended for navigation links. It includes a list of links to other parts of the site.
    ```html
    <nav>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">Article</a></li>
            <li><a href="">Our Contact</a></li>
        </ul>
    </nav>
    ```

3. **`<section>`**: Defines a section of content, typically with a heading. This example contains two articles.
    ```html
    <section>
        <article>
            <h1>Studying HTML</h1>
            <p>HTML Subject</p>
        </article>
        <article>
            <h1>Studying CSS</h1>
            <p>CSS Subject</p>
        </article>
    </section>
    ```

4. **`<article>`**: Represents a self-contained composition in a document, page, or site that is independently distributable or reusable. Here, it is used for individual pieces of content within the section.
    ```html
    <article>
        <h1>Studying HTML</h1>
        <p>HTML Subject</p>
    </article>
    <article>
        <h1>Studying CSS</h1>
        <p>CSS Subject</p>
    </article>
    ```

5. **`<footer>`**: Defines the footer for a document or section. It usually contains metadata about the document or the author. In this example, it includes a copyright notice and the year.
    ```html
    <footer>
        <p>Powered by Nazmi Hakim <time datetime="2024">2024</time></p>
    </footer>
    ```

## Benefits of Semantic HTML

- **Accessibility**: Semantic HTML elements provide meaning to the web content, making it more accessible to screen readers and assistive technologies.
- **SEO**: Search engines can better understand the structure and content of the web page, which can improve search rankings.
- **Maintainability**: Using semantic elements helps create a more organized and readable codebase, making it easier to maintain and update.

By using semantic HTML, developers can create web pages that are more meaningful, accessible, and easier to manage.
