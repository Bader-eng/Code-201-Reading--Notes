# css:
## Key Concepts in positioning eLements:
1. Building Blocks:
CSS treats each HTML element as if it is in its own box. This box will either be a block-levelbox or an inline box.
2. Block-level elementsstart on a new lineExamples include:h1 p ul li
3. inline elements flow in Between surrounding text
4. containing Elements:If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element
## ControLLing the position of eLements:
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the positionproperty in CSS. You can also float elements using the float property.
1. normal flow:Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-by-side, they will not appear next to each other.
2. relative Positioning:This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they w
ould be in in normal flow.
3. absolute Positioning:
This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
### normaL fLow:
In normal flow, each block-level element sits on top of the next one.
### reLative positioning:
Relative positioning moves an element in relation to where it would have been in normal flow
### absoLute positioning:
When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)
### fixed positioning:
Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.
### over Lapping eLements:

# screen sizes:
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
## screen resoLution:
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
## page sizes:
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).
