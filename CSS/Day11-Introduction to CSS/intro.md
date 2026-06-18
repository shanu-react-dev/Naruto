# CSS

_CSS stands for Cascading Style Sheets. It is used to add stylings and positioning to our HTML elements. We can add animations as well using our CSS. It is responsible for making the UI to look good._

_We can add CSS in various ways as follows._

1.  **Inline CSS:** Using inline CSS we can change the appearance of the elements. We can write Inline CSS using style attribute in the opening tag of our elements.

    Syntax:

    ```html
    <h2 style="color: red">Hii this is Inline css</h2>
    ```

2.  **Internal CSS:** Internal CSS can be used in our HTML file using style tag. We should always write internal CSS in head tag. It is a good practice.

    Syntax:

    ```html
    <html>
      <head>
        <style>
          h2 {
            color: blue;
          }
        </style>
      </head>
      <body>
        <h2>Hi this is Internal CSS</h2>
      </body>
    </html>
    ```

3.  **External CSS:** This is the standard way to add the CSS to HTML file and widely used in IT industries. It provides separation of concern. We can create a new file having extension as `.css` and we need to link the file in our HTML file using `link` tag. It should be linked in head tag only (good practice).

    Syntax:

    ```html
    <html>
      <head>
        <link rel="stylesheet" href="./file.css" />
      </head>
      <body>
        <h2>Hi this is Internal CSS</h2>
      </body>
    </html>
    ```
