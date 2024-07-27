```markdown
# Reserved Characters and Entities in HTML

## Introduction
In HTML, certain characters are reserved and have special meanings. To display these characters correctly in a web page, you need to use character entities. This README will guide you through the common reserved characters and their corresponding HTML entities.

## Reserved Characters

### Common Reserved Characters
These characters are reserved in HTML and must be represented by character entities to be displayed properly:

- `<` (less than) should be written as `&lt;`
- `>` (greater than) should be written as `&gt;`
- `&` (ampersand) should be written as `&amp;`
- `"` (double quote) should be written as `&quot;`
- `'` (single quote) should be written as `&apos;`

### Example Usage
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Reserved Characters Example</title>
    </head>
    <body>
        <p>To display a less than sign, use &lt; instead of <.</p>
        <p>To display a greater than sign, use &gt; instead of >.</p>
        <p>To display an ampersand, use &amp; instead of &.</p>
        <p>To display double quotes, use &quot; instead of ".</p>
        <p>To display single quotes, use &apos; instead of '.</p>
    </body>
</html>
```

## Character Entities
Character entities are used to display characters that are reserved in HTML or those that might not be readily available on a keyboard. They are written as `&` followed by an entity name or a number and then `;`.

### Named Entities
Here are some common named entities:

- `&lt;` for <
- `&gt;` for >
- `&amp;` for &
- `&quot;` for "
- `&apos;` for '

### Numeric Entities
Numeric entities use the character's Unicode code point:

- `&#60;` for <
- `&#62;` for >
- `&#38;` for &
- `&#34;` for "
- `&#39;` for '

### Example Usage
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Character Entities Example</title>
    </head>
    <body>
        <p>Named entity for less than: &lt;</p>
        <p>Named entity for greater than: &gt;</p>
        <p>Named entity for ampersand: &amp;</p>
        <p>Named entity for double quotes: &quot;</p>
        <p>Named entity for single quotes: &apos;</p>
        <p>Numeric entity for less than: &#60;</p>
        <p>Numeric entity for greater than: &#62;</p>
        <p>Numeric entity for ampersand: &#38;</p>
        <p>Numeric entity for double quotes: &#34;</p>
        <p>Numeric entity for single quotes: &#39;</p>
    </body>
</html>
```

## Conclusion
Using the correct character entities in HTML ensures that reserved characters are displayed properly, avoiding potential issues in your web page's rendering. Understanding and using these entities will help you write more robust and error-free HTML code.
