```markdown
# Inline Frame Example

This project demonstrates the use of an inline frame (`<iframe>`) in HTML. It includes two HTML files: `inline-frame.html` and `color.html`.

## Files

### 1. inline-frame.html

This file contains the main content and includes an inline frame that loads the content from `color.html`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline Frame</title>
</head>
<body>
    <h1>Inline Frame</h1>
    <iframe src="color.html" frameborder="0" height="500px" width="1000px"></iframe>
</body>
</html>
```

### 2. color.html

This file contains the content displayed inside the inline frame. It features three headers with different background colors specified using different color formats.

```html
<!DOCTYPE html>
<html>
    <body>
        <h1 style="background-color: #14e867;">Studying HTML</h1>
        <h1 style="background-color: rgb(255, 252, 64);">Studying HTML</h1>
        <h1 style="background-color: hsl(335, 100%, 59%);">Studying HTML</h1>
    </body>
</html>
```

## How to Use

1. Ensure both `inline-frame.html` and `color.html` are in the same directory.
2. Open `inline-frame.html` in a web browser.
3. The content from `color.html` will be displayed within an inline frame inside `inline-frame.html`.

## Explanation

### inline-frame.html

- This file sets up the structure of the main page.
- The `<iframe>` tag is used to embed another HTML document (`color.html`) within the main page.
- The `src` attribute of the `<iframe>` tag specifies the URL of the page to embed.
- The `frameborder`, `height`, and `width` attributes are used to style the frame.

### color.html

- This file contains three `<h1>` headers with different background colors.
- The colors are specified using different color formats:
  - Hexadecimal (`#14e867`)
  - RGB (`rgb(255, 252, 64)`)
  - HSL (`hsl(335, 100%, 59%)`)

## Notes

- Make sure the `src` attribute in the `<iframe>` tag correctly points to the `color.html` file location.
- You can adjust the `height` and `width` attributes of the `<iframe>` tag to fit your layout requirements.
