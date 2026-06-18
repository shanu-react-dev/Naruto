## Combinator Selectors in CSS

_Combinator Selectors helps us to target the multiple elements at the same time based on relations of the elements._

_There are total 4 combinator Selectors._

1.  **Descendent Selectors:** This selector helps us to target the direct child or indirect child elements of an element. We can use it by specifying one space between parent element and target element.

    Syntax:

        ```css
        <!-- parentElement targetElement{
            properties: value
        } -->

        div h1{
            color: blue;
        }
        ```

    _In the above examples it will target the all `h1` element which falls under `div` tag and make the color as blue._

2.  **Child Selector:** This selector helps to target the nearest child element of an element (parent). We can use this selector by specifying greater than symbol `>` between parent element and target element.

    Syntax:

    ```css
    div > h1 {
      color: red;
    }
    ```

    _In the above example here only `h1` element will be targeted that also which is the direct child of `div` tag not the indirect `h1` element._

3.  **Adjacent Sibling Selector:** This selector helps us to target the nearest sibling element (just after). we can use this selector by specifying plus `+` symbol between the first sibling element and targeted sibling element.

    Symbol:

    ```css
    h1 + p {
      background: pink;
    }
    ```

    _In the above example only `p` tag will be targeted which is used just after `h1` tag as a sibling element._

4.  **General Sibling Selector:** This selector helps us to target the all sibling elements for a sibling element. We can use this selector by specifying tilde `~` symbol between two sibling elements.

    Syntax:

    ```css
    h1 ~ p {
      color: blue;
    }
    ```

    _In the above example all Paragraph will be targeted which is used as a sibling of h1._
