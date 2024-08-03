# Tables in HTML

### Introduction

HTML tables are a powerful tool for displaying tabular data. They allow for the clear presentation of information in rows and columns. This README explains the basics of creating and styling tables in HTML, including the use of `<table>`, `<tr>`, `<td>`, `<th>`, and more advanced elements like `<colgroup>`, `colspan`, and `rowspan`.

### Table Structure

A basic HTML table structure includes the following elements:

- `<table>`: Defines the table.
- `<tr>`: Defines a table row.
- `<td>`: Defines a table cell.
- `<th>`: Defines a table header cell.

### Example 1: Basic Table with Styling

#### Code: `table.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
</head>
<body>
    <table style="border: 1px solid black;">
        <colgroup>
            <col span="2" style="background-color: yellow;">
            <col style="background-color: aqua;">
        </colgroup>
        <thead>
            <tr>
                <th>First Name</th>
                <th>Last Name</th>
                <th>Value</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Nazmi</td>
                <td>Hakim</td>
                <td>93</td>
            </tr>
            <tr>
                <td>Teramoz</td>
                <td>Gatsu</td>
                <td>81</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td></td>
                <td>Total</td>
                <td>174</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```

#### Explanation

- `<colgroup>` and `<col>` are used to style columns. The first two columns have a yellow background, and the third column has an aqua background.
- The `<thead>` element contains header rows.
- The `<tbody>` element contains the main content of the table.
- The `<tfoot>` element contains the footer rows.

### Example 2: Table with `colspan` and `rowspan`

#### Code: `colspan-and-rowspan.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
</head>
<body>
    <table style="border: 1px solid black;">
        <colgroup>
            <col span="2" style="background-color: yellow;">
            <col style="background-color: aqua;">
        </colgroup>
        <thead>
            <tr>
                <th colspan="2">Name</th>
                <th>Value</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Nazmi</td>
                <td>Hakim</td>
                <td>93</td>
            </tr>
            <tr>
                <td>Teramoz</td>
                <td>Gatsu</td>
                <td>81</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td rowspan="2">Total</td>
                <td>Total</td>
                <td>174</td>
            </tr>
            <tr>
                <td>Rata-Rata</td>
                <td>80</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```

#### Explanation

- The `<colspan>` attribute in `<th colspan="2">Name</th>` is used to make the "Name" header span across two columns.
- The `<rowspan>` attribute in `<td rowspan="2">Total</td>` is used to make the "Total" cell span across two rows in the footer.
- The rest of the table structure is similar to the first example, with a `<colgroup>` for styling and `<thead>`, `<tbody>`, and `<tfoot>` for organizing the table content.

### Conclusion

HTML tables provide a robust way to display structured data on the web. By using various HTML elements and attributes, you can create clear and well-styled tables. The examples provided demonstrate the basic usage and some advanced features like column and row spanning.
