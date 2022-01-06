# Learning CSS - Cascading Style Sheets

## [CSS Cheat Sheet](https://htmlcheatsheet.com/css/)
- Is a language to describe the appearance visually - how they are arranged and styled.

## CSS Rules
  - (almost) everything you do in CSS follows the same pattern.

## CSS Colors
  - "The **RGB color model** is an additive color model in which the red, green, and blue primary colors of light are added together in various ways to reproduce a broad array of colors. The name of the model comes from the initials of the three additive primary colors, red, green, and blue."
  - RGB - each chanel goes from 0 - 255
  - `rgb(255, 0, 0)` - maxed out red with no green and no blue
  - black is `rgb(0, 0, 0)`
  - There are color picking apps because it'd be pretty hard to try and remember all numbers for each color scheme.
  - **Hex** still red, green, and blue.
  - Each ranges from 0-255, but represents with hexadecimal.
  - Every digit is a decimal

  - `px` is not recommended for responsive websites
  - `px` is supposed to resemble pixels on your screen, but not across all machines. There are better units to use for modern web developement.
  - `font-family` changing fonts is not as easy as it seems, because you are relying on browser fonts and they might not be supported.
  - **Font stack** is used to allow the browser to fall back if the font specified in your CSS isn't available.

  ## Selectors
  - `*` - Universal Selector (Not commonly used)
  - You can use a comma to select/combine multiple elements.

  ## Decendant Selector
  - To select an element that nested in an element you would write <br>
  `li a {`<br>
    `color: blue`<br>
  `}`<br>
  - There is a space inbetween two elements and this would select all `a` elements inside the `li` elements.
  - No `li's` will be styled. Just `a`

  ## Adjecent Selector
  - Technically called combinator<br>
    `h1 + p {`<br>
       `color: red;`<br>
    `}`<br>
  - This would select only the paragraphs that are immediately preceded by an `<h1>`
  - They are adjecent, not children or parents

  ## Direct Child
    div > li {
      color: white;
    }
  - Select only the `<li>'s` that are direct children of a `<div>` element<br>

  ## Attribute Selector
  `input[type="text"] {`<br>
    `width: 300px;`<br>
    `color: yellow;`<br>
  `}`<br>

  ## Pseudo Classes
  `a:hover {`<br>
    `color: orange;`<br>
    `background-color: brown`<br>
  `}`<br>
  - Keyword  added to a selector that specifies a special state of the selected elements.
  - All of these start with a colon.<br>
  `.post:nth-of-type(3n) {`<br>
    `color: orange;`    - This will select every third post<br>
    `background-color: brown`<br>
  `}`<br>

  ## Psuedo Elements
  - Keyword added to a selector that lets you style a particular part of selected element(s).
  - `::after`
  - `::before`
  - `::first-letter`
  - `::first-line`
  - `::selection`
  - Should have two colons

  ## Cascade
  - The order your styles are declared in and linked to matters!
  - If there are two conflicting styles, the latter takes precedence because CSS is CASCADING :)

  ## Specificity
  - What happens when conflicting styles target the same elements?
  - Specificity is how the browser decides which rules to apply when multiple rules could apply to the same element.
  - It is a measure of how specific a given selector is. The more specific selector "wins"