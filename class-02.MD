# HTML TEXT
## HTML has six "levels" of headings:
1. <h1> is used for main headings
2. <h2> is used for subheadings
3. If there are further sections under the subheadings then the <h3> element is used, and so on

## paragraph :
To create a paragraph, surround the words that make up the paragraph with an opening <p>tag and closing </p> tag
## Bold & italic :
1. By enclosing words in the tags <b> and </b> we can make characters appear bold.
2. By enclosing words in the tags <i> and </i> we can make characters appear italic.
## Superscript & Subscript:
1. The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.
2. The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

## strong & emphasi:
1. The use of the <strong>element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.
2. The <em> element indicates emphasis that subtly changes the meaning of a sentence.

# css :

## using externaL css:
1. The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page.
2. href: This specifies the path to the CSS file (which is often placed in a folder called css or styles).
3. type :This attribute specifies the type of document being linked to. The value should be text/css
4. rel:This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
## using InternaL css:
1. <style>:You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page.
2. There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. 
CSS selectors are case sensitive, so they must match element names and attribute values exactly.
![CSS selectors](https://csharpcorner.azureedge.net/UploadFile/9a9e6f/selectors-in-css/Images/types%20of%20selectors.jpg)

## how css ruLes cascade:
1. Last rule: f the two selectors are identical, the latter of the two will take precedence. Here you can  see the second i selector takes precedence over the first.
2. SpecIfIcit:If one selector is more specific than the others, the more specific rule will take precedence over more general ones
3. important:You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

# script :
1. A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 
2. You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.
3.  script will have to temporarily store the bits of information it needs to do its job. It can store t his data in variables. When you write JavaSc

4. DATA TYPES:
* NUMERIC DATA TYPE
* STRING DATA TYPE 
* BOOLEAN DATA TYPE 
5. USING A VARIABLE: 
* TO STORE A NUMBER 
* TO STORE A STRING
* TO STORE A BOOLEAN