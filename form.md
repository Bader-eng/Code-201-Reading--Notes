# Form Controls:
1. adding text:
* Text input :
Used for a single line of text such as email addresses and names.
* Password input :Like a single line text box but it masks the characters entered.
* Text area (multi-line):For longer areas of text, such as messages and comments.
2. Making Choiocs:
* Radio buttons:For use when a user must select one of a number of options.
* Checkboxes:When a user can select and unselect one or more options.
* Drop-down boxes:When a user must pick one of a number of options from a list.
3. submitting Forms:
* Submit buttons:To submit data from your form to another web page.
* Image buttons:Similar to submit buttons but they allow you to use an image.
4. uploading File:Allows users to upload files (e.g. images) to a website

## how Forms Work:
1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received

 ## Form struCture:
 * <form>:Form controls live inside a <form> element. This element should always carry the actionattribute and will usually have a method and id attribute too.
 * action:Every <form> element requires an action attribute. Its valueis the URL for the page on the server that will receive the information in the form when it is submitted.
 * method:
 * id

 ### text Input:
 * The <input> element is used to create several different form controls. The value of the typeattribute determines what kind of input they will be creating
 * When the type attribute has a value of text, it creates a single-line text input.
 
 ## Unordered Lists:
 none   disc   circle   square

 1. ordered Lists:
 * decimal
 * decimal-leading-zero
 *  lower-alpha
 * upper-alpha
 * lower-roman
 * upper-roman 
 ## list-style-position:
 * outside
 * inside
 ## tabLe ProPerties:
 width
 padding
 text-transform
 letter-spacing, font-size
 border-top, border-bottom

 ## DIFFERENT EVENT TYPES 
 * load: Web page has finished loading 
 * unload :Web page is unloading (usually because a new page w as requested) 
 * error :Browser encounters a JavaScript error or an asset doesn't exist
 * resize :Browser window has been resized
 * scroll :User has scrolled up or down the page

 ## HOW EVENTS TRIGGER JAVASCRIPT CODE :
 1. Select t he element node(s) you want the script to respond to.
 2. Indicate which event on the selected node(s) will trigger the response.
 3. State the code you want to run when the event occurs
