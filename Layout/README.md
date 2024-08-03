```markdown
# Semantic HTML Layout

This project demonstrates a simple semantic HTML layout with basic styling. The structure includes a header, navigation bar, main content section, and footer.

## File Structure

```
.
├── index.html
├── README.md
```

## HTML Structure

### Header
The header contains the page title and is styled with a gray background and white text.

```html
<header>
    <h1>Page Title</h1>
</header>
```

### Navigation Bar
The navigation bar provides links to different sections of the site. It has a yellow background and changes to orange when a link is hovered over.

```html
<nav>
    <ul>
        <li><a href="">Home</a></li>
        <li><a href="">Article</a></li>
        <li><a href="">Our Contact</a></li>
    </ul>
</nav>
```

### Main Content
The main content section contains multiple articles. Each article is enclosed in an `<article>` tag and includes a heading and a paragraph.

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

### Footer
The footer includes a credit and the current year. It has a gray background and white text.

```html
<footer>
    <p>Powered by Nazmi Hakim <time datetime="2024">2024</time></p>
</footer>
```

## CSS Styling

The CSS styles are embedded within the `<style>` tag in the `<head>` section of the HTML document. The styles are as follows:

```css
header {
    background-color: gray;
    padding: 30px;
    text-align: center;
    font-size: 35px;
    color: white;
}
article {
    padding: 20px;
    width: 100%;
    background-color: aliceblue;
}
footer {
    background-color: grey;
    padding: 10px;
    text-align: center;
    color: white;
}
nav {
    background-color: yellow;
    padding: 10px;
}
nav ul {
    list-style-type: none;
    overflow: hidden;
}
nav li {
    float: left;
}
nav li a {
    display: block;
    text-align: center;
    padding: 10px;
    text-decoration: none;
}
nav li a:hover {
    background-color: orange;
}
```

## Conclusion

This project showcases a simple HTML layout using semantic elements and basic CSS styling. It serves as a foundational example for building more complex web pages.
