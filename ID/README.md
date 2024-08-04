```markdown
# HTML Document: ID Usage

This HTML document demonstrates the use of the `id` attribute to uniquely identify and style elements within a web page.

## Overview

The document contains two `<h1>` elements, each with a unique `id` attribute (`top` and `bottom`). These IDs are used to apply different CSS styles to the elements.

### HTML Structure

The HTML file is structured as follows:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ID</title>
    <style>
        #top {
            color: red;
        }

        #bottom {
            color: blue;
        }
    </style>
</head>
<body>
    <h1 id="top">This is Top</h1>
    <h1 id="bottom">This is Bottom</h1>
</body>
</html>
```

### Key Elements

- **Document Type Declaration**: `<!DOCTYPE html>` indicates that this document is an HTML5 document.
- **HTML Tag**: `<html lang="en">` specifies the language of the document as English.
- **Head Section**: Contains metadata, including character set and viewport settings, as well as the title and embedded CSS styles.
- **Body Section**: Contains the content of the web page, including the two `<h1>` elements.

### ID Attributes

The document uses the `id` attribute to apply unique styles to each `<h1>` element:

- **Top Header**:
  ```html
  <h1 id="top">This is Top</h1>
  ```
  - Styled with the `#top` CSS selector:
    ```css
    #top {
        color: red;
    }
    ```

- **Bottom Header**:
  ```html
  <h1 id="bottom">This is Bottom</h1>
  ```
  - Styled with the `#bottom` CSS selector:
    ```css
    #bottom {
        color: blue;
    }
    ```

### CSS Styling

The styles are defined within the `<style>` tag in the `<head>` section. The `id` selectors `#top` and `#bottom` are used to apply the colors red and blue, respectively:

```css
#top {
    color: red;
}

#bottom {
    color: blue;
}
```

### Result

When rendered in a browser, the page displays two headers:
- "This is Top" in red.
- "This is Bottom" in blue.

## Conclusion

This document illustrates a simple example of how to use the `id` attribute in HTML to uniquely identify and style elements. The `id` attribute allows for precise targeting of elements with CSS for customized styling.
