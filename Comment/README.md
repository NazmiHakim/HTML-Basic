```markdown
# HTML Comments

## Overview

HTML comments are used to insert notes or reminders in the code that will not be displayed on the web page. Comments can be used to explain the HTML, which can be helpful when editing the source code at a later date. They are also useful for debugging by temporarily disabling parts of the code.

## Syntax

HTML comments start with `<!--` and end with `-->`. Any content placed between these markers will be treated as a comment and will not be rendered by the browser.

```html
<!-- This is a comment -->
<p>This is not a comment and will be displayed.</p>
```

## Usage

### Adding Explanatory Notes

You can add comments to explain what a particular section of the code does. This can be helpful for yourself or others who may work on the code in the future.

```html
<!-- This section contains the navigation links -->
<nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
</nav>
```

### Temporarily Disabling Code

If you need to temporarily disable a piece of code without deleting it, you can comment it out.

```html
<!-- <p>This paragraph is commented out and will not be displayed.</p> -->
<p>This paragraph will be displayed.</p>
```

### Debugging

When troubleshooting issues in your HTML code, you can comment out parts of the code to identify where the problem is occurring.

```html
<!-- <div class="sidebar">Sidebar content</div> -->
<div class="main-content">Main content</div>
```

## Best Practices

- Use comments sparingly. Overusing comments can make the HTML code cluttered and difficult to read.
- Make comments meaningful. Avoid adding comments that do not add value, such as `<!-- This is a comment -->`.
- Be consistent with your commenting style. Use a standard format for comments to maintain readability.

## Examples

### Example 1: Basic Comment

```html
<!-- This is a single-line comment -->
<p>This paragraph will be displayed.</p>
```

### Example 2: Multi-line Comment

```html
<!--
This is a multi-line comment.
It can span multiple lines.
-->
<p>This paragraph will be displayed.</p>
```

### Example 3: Commenting Out Code

```html
<!--
<h1>Title</h1>
<p>This paragraph is commented out and will not be displayed.</p>
-->
<p>This paragraph will be displayed.</p>
```

## Conclusion

HTML comments are a useful tool for documenting your code, temporarily disabling sections, and aiding in debugging. By using comments effectively, you can make your HTML code more understandable and maintainable.
