# Block and Inline Elements in HTML

HTML elements can be broadly classified into two categories: **block-level elements** and **inline elements**. Understanding the difference between these two types is crucial for effective web design and layout. Below, we'll discuss these concepts with examples.

## Block-Level Elements

Block-level elements occupy the entire horizontal space of their parent element (container), and they start on a new line. Common block-level elements include `<div>`, `<h1>` to `<h6>`, `<p>`, and `<ul>`. These elements are used to structure the main layout of a web page.

### Example: div.html

```html
<!DOCTYPE html>
<html>
    <body>
        <div id="menu" style="background-color: yellow;">
            <ul>
                <li>Home</li>
                <li>Article</li>
                <li>Social Media</li>
            </ul>
        </div>
        <div id="content" style="background-color: pink;">
            <h1>Page Title</h1>
            <p>Page Content:</p>
        </div>
        <h1 style="background-color: aqua;">Example</h1>
    </body>
</html>
```

#### Explanation:
- `<div>`: A generic container used to group other elements. It is a block-level element.
- `<h1>`: A heading element, also block-level. It starts on a new line and takes up the full width.
- `<ul>`: An unordered list, also block-level. It contains list items `<li>`, which are block-level by default.
- `<p>`: A paragraph element, block-level, starting on a new line and taking up full width.

## Inline Elements

Inline elements do not start on a new line. They only take up as much width as necessary and allow other elements to sit beside them. Common inline elements include `<span>`, `<a>`, `<img>`, and `<strong>`.

### Example: span.html

```html
<!DOCTYPE html>
<html>
    <body>
        <h1>
            <span style="color: red;">Nazmi</span>
            <span style="color: blue;">Hakim</span>
            <span style="color: yellow;">HTML</span>
        </h1>
    </body>
</html>
```

#### Explanation:
- `<span>`: A generic inline container used to style parts of text or other inline elements. It does not start on a new line and only takes up as much width as needed.
- In this example, the `<span>` elements are used to color different parts of the heading text without affecting the overall layout. They remain inline with the text within the `<h1>` element.

## Key Differences

- **Block-level elements**:
  - Start on a new line.
  - Take up the full width available.
  - Used for larger structural pieces of content.

- **Inline elements**:
  - Do not start on a new line.
  - Only take up as much width as needed.
  - Used for smaller pieces of content within block-level elements.

Understanding these distinctions helps in creating a well-structured and visually appealing web page by properly utilizing the space and organizing the content efficiently.
