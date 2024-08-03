```markdown
# Responsive HTML Example

This project demonstrates basic responsive design principles in HTML using relative units such as `vw` (viewport width) for font sizes and percentages for image dimensions. The provided HTML file is a simple example that adjusts text size and image dimensions based on the viewport size.

## Table of Contents
- [Overview](#overview)
- [Files Included](#files-included)
- [Responsive Techniques Used](#responsive-techniques-used)
- [Usage](#usage)
- [Browser Compatibility](#browser-compatibility)
- [Contributing](#contributing)
- [License](#license)

## Overview
Responsive design ensures that web content adapts smoothly to various screen sizes and devices, providing an optimal viewing experience. This example includes:
- A heading that scales with the viewport width.
- A paragraph that scales with the viewport width.
- An image that adjusts its width to fit the container while maintaining its aspect ratio.

## Files Included
- `index.html`: The main HTML file containing the responsive design example.
- `ayang2.jpg`: An example image used in the HTML file.

## Responsive Techniques Used
1. **Viewport Width (vw)**: The `vw` unit is used to set the font size relative to the viewport width, ensuring the text scales with the size of the browser window.
    ```html
    <h1 style="font-size: 5vw;">Studying Responsive</h1>
    <p style="font-size: 2vw;">Studying Responsive</p>
    ```

2. **Percentage Width**: The image width is set to `100%`, allowing it to resize according to its parent container's width while maintaining its aspect ratio using `height: auto`.
    ```html
    <img style="width: 100%; height: auto;" src="ayang2.jpg" alt="Webtoon Character">
    ```

## Usage
1. Open `index.html` in a web browser.
2. Resize the browser window to observe how the text and image adjust responsively.

## Browser Compatibility
This example uses basic HTML and CSS that are widely supported by all modern browsers, including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Contributing
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
```
