# Learning CSS - Cascading Style Sheets

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
  - `#` - selector