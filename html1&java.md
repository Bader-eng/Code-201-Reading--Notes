# LIST :
Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute 
1. Linking to other sites:Links are created using the <a>element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link 
2. Linking to other pages on the same site:When you are linking to other pages within the same site, you do not need to specify the domain name in 
the URL. You can use a shorthand known as a relative URL

## reLative urls:
Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
* reLative Link type:
1. same Folder:to link to a file in the same folder, just use the file name. 
2. child Folder:For a child folder, use the name of the child folder, followed by a forward slash, then the file name
3. parent Folder:Use ../ to indicate the folder above the current one, then follow it with the file name.
##  mailto:
to create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a>element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

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

# js :
## WHAT IS A FUNCTION?:
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements)
## The function declaration:
 (function statement) defines a function with the specified parameters.
 You can also define functions using the Function constructor and a function expression.
 ![function](https://res.cloudinary.com/practicaldev/image/fetch/s--Hs9oP1kt--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/2s0ow3sewsla01mp5xur.png)

## ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS :
1. A function declaration: creates a function that you can call later in your code. It is the type of function you have seen so far in this book.
2. FUNCTION EXPRESSION :
If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression
## Pair Programming:
pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together

### Why pair program?:
1. Greater efficiency
2. Engaged collaboration:When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone
3. Learning from fellow students:
4. Social skills:Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key
5. Job interview readiness
6. Work environment readiness