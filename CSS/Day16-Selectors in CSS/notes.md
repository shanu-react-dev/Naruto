## Pseudo Class Selector

_Pseudo Class Selector is a keyword which is used to style the HTML elements based on their state. If we want to change the state of an element then we can use it._

_We need to use pseudo class selector with the following syntax. It must and should followed by targeted element and single colon_

```css
h1:hover {
  color: green;
}
```

_Here in the above example hover is a pseudo class selector. Whenever will move the mouse on the specified element it will be changing the color in green._

_Few pseudo class selectors are listed below._

1. :hover: It is used to change the behavior of an element while moving cursor on the element.
2. :focus: It is used to change the behavior of input when it is focused.
3. :active: It is used to change the behavior of an element while clicking the element or when it is active.
4. :first-child: Helps to target the first child element in HTML
5. :last-child: Helps to target the last element in HTML
6. :nth-child(): this allows us to target the specific element from a group such as specific number of list in an HTML. We can target here odd or even number of items as well by specifying odd or even in parentheses.

## Pseudo Element Selector

_This is also a keyword and used to change the specific part of an element. It must and should be followed by double colon and targeted element._

```css
h1::first-letter {
  color: green;
}
```

_In the above example `first-letter` is pseudo ELement selector and it will be changing the behavior of first letter of Heading._

_few Pseudo Element selectors are listed below_

1. ::after
2. ::before
3. ::first-line
4. ::first-letter
5. ::marker
6. ::selection
