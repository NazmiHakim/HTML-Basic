```markdown
# HTML Formatting Tags

This document explains the various HTML formatting tags used in the given example.

## Example HTML Code

```html
<html>
    <body>
        <p>
        Hi <b>Teramoz</b>, Good Luck <i>Studying HTML</i> with <strong>Nazmi Hakim</strong>
        </p>   
        <p>
            Don't <del>Be Pessimist</del> Okay? Keep The <ins>Spirit</ins> Up
        </p> 
        <p>2<sup>2</sup> = 4</p>
    </body>
</html>
```

## Tags Explanation

### `<b>` and `<strong>`

- **`<b>`**: The `<b>` tag is used to make the enclosed text bold. It does not convey any extra importance or emphasis.
    ```html
    Hi <b>Teramoz</b>
    ```
  This will render as: Hi **Teramoz**

- **`<strong>`**: The `<strong>` tag is used to indicate that the enclosed text is of strong importance. Browsers will render it in bold by default.
    ```html
    with <strong>Nazmi Hakim</strong>
    ```
  This will render as: with **Nazmi Hakim**

### `<i>`

- **`<i>`**: The `<i>` tag is used to italicize the enclosed text. It is often used to denote a different tone or voice, such as a technical term or a thought.
    ```html
    Good Luck <i>Studying HTML</i>
    ```
  This will render as: Good Luck *Studying HTML*

### `<del>`

- **`<del>`**: The `<del>` tag is used to indicate that the enclosed text has been deleted or is no longer relevant. Browsers typically render this text with a strikethrough.
    ```html
    Don't <del>Be Pessimist</del>
    ```
  This will render as: Don't ~~Be Pessimist~~

### `<ins>`

- **`<ins>`**: The `<ins>` tag is used to indicate that the enclosed text has been inserted or is newly added. Browsers typically render this text with an underline.
    ```html
    Keep The <ins>Spirit</ins> Up
    ```
  This will render as: Keep The <ins>Spirit</ins> Up

### `<sup>`

- **`<sup>`**: The `<sup>` tag is used to define superscript text. This text will be rendered half a character above the baseline, making it useful for footnotes, mathematical exponents, etc.
    ```html
    2<sup>2</sup> = 4
    ```
  This will render as: 2² = 4

## Complete Rendered HTML

The provided HTML code will render as follows:

Hi **Teramoz**, Good Luck *Studying HTML* with **Nazmi Hakim**

Don't ~~Be Pessimist~~ Okay? Keep The <ins>Spirit</ins> Up

2² = 4
