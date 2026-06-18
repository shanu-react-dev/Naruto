## Selectors

_It is a way to target or select the HTML elements. There are various selectors in CSS as follows._

1.  **Simple Selectors:** There are many selectors in CSS one of them is simple selector contains total 5 simple selectors as follows.
    1. **ID Selector:** Using this selector we can target the specific element using their ID. It is an attribute given to HTML elements to make the element unique. ID selector is unique it accepts only one value. In CSS we can target any element having ID using special symbol `#`.

       Syntax:

       ```css
       #idName {
         color: blue;
       }
       ```

       _ID selector will have the highest priority among all simple selectors._

    2. **class Selector:** This selector allows us to target any element based on their classnames. class is an attribute used to give the name to the HTML elements. It can accept multiple values. To target any element with their class name in CSS we need to use `.` symbol.

       Syntax:

       ```css
       .className {
         color: red;
       }
       ```

       _Class selector is having the second highest priority among all simple selectors._

    3. **Tagname Selector:** Tagname selector helps us to target the elements by using their names. It selects the entire specified elements in the file and applies the stylings for all tags.

       Syntax:

       ```css
       p {
         background: lightseagreen; /*Selects all paragraphs in the file and adds background color as lightseagreen*/
       }
       ```

       _It will have the third highest priority among simple selectors._

    4. **Grouping Selector:** Grouping selector allows us to target the multiple elements at the same time and same stylings. If we want to give same stylings for multiple elements then we can use this. Multiple elements needs to be separated using `,`.

       Syntax:

       ```css
       h1,
       p {
         background: lightpink; /*It will target all h1 and p tag in the file and add the bgcolor as lightpink*/
       }
       ```

       _Here priority depends on the use cases but we can say it is having 4th priority in simple selectors._

    5. **Universal Selector:** This is the last and most important selector used to target the all elements at the same time. If I want to keep the same styling for each and every element then we can use this. To use universal selector we need to use `*` symbol.

       Syntax:

       ```css
       * {
         background: #fff; /*It will add the white color as a background for each and every element.*/
       }
       ```

       _It is having the last priority. It should be used at the top of the CSS file._
