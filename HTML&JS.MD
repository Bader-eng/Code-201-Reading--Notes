# HTML&JS.MD

## INTRODUCTION:
### how PeopLe access the web:
1. **Browsers**: People access websites using software called a web browser. Popular examples include Firefox,
Internet Explorer, Safari, Chrome, and Opera.

2. **Web servers**: When you ask your browser for a web page, the request is sent across the Internet 
to a special computer known as a web server which hosts the website.
Some big companies run their own web servers, but it is more common to use the services 
of a web hosting c'ompany who charge a fee to host your site.

3. **Screen readers**: are programs that read out the contents of a computer screen to a user. 
 They are commonly used by people with visual impairments.
 
## how websites are created:
Small websites are often written just using HTML and CSS.Larger websites — in particular those that are updated regularly and use a content management system (CMS), 
blogging tools, or e-commerce software — often make use of more complex technologies on the web server

## how the web works:
1. When you connect to the web, you do so via an Internet Service Provider (ISP). 
You type a domain name or web address into your browser to visit a site.
2. Your computer contacts a network of servers called Domain Name System (DNS) servers. These act like phone books;
 they tell your computer the IP address associated with the requested domain name.
3. The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested. 
A web server is a computer that is constantly connected to the web, and is set up especially to send web pages to users.
4. The web server then sends the page you requested back to your web browser.

![how the web works](https://res.cloudinary.com/academind-gmbh/image/upload/f_auto,q_auto/c_limit,dpr_3.0,g_center,w_400/v1/academind.com/content/tutorials/how-the-web-works/how-the-web-works-big-picture)

### htmL uses eLements to describe tHe Structure of Pages:

![html elements](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDEvaxCPpk3DF6E4vugvzbkL7kJGnxiGHHQw&usqp=CAU)

1. **Tags**: act like containers. They tell you something about the information that lies between their opening and closing tags 
2. **Attributes**: provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts:
a name and a value, separated by an equals sign.
3. **<body>**:Everything inside this element is shown inside the main browser window.
4. **<head>**:This contains information about the page (rather than information that is shown within 
the main part of the browser window that is highlighted in blue on the opposite page). 
5. **title** :The contents of the <title> element are either shown in the top of the browser, above where you usually
type in the URL of the page you want to visit, or on the tab for that page 
# EXTRA MARKUP
## DOCTYPE :
tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).
## id attribute:
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page
## Class attribute :
Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page.
## block level :elements will always appear to start on a new line in the browser window.
 
## grouping text and elemints"
* The <div> :element allows you to group a set of elements together in one block-level box.
* The <span>: element acts like an inline equivalent of the <div>element. It is used to either:
  1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
  2. Contain a number of inline elements
* Iframe: is like a little window that has been cut into your page — and in that window you can see another page. 
The term iframe is an abbreviation of inline frame.
 # Escape Characters:
1. There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets)
2. Therefore, if you want these characters to appear on your page you need to use what are termed "escape" characters (also known as escape codes or entity references)
3. There are also special codes that can be used to show symbols such as copyright and trademark, currency symbols, mathematical characters, and some punctuation marks.
### example:
1. Pound sign :&pound; &#163
2. Less-than sign: &lt;   &#60;
3. Cent sign:&cent;&#162;
4. Copyright symbol &copy;&#169;
 
 ## New HTML5 layout eLements :
HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. 
1. header and footer :The main header or footer ●that appears at the top or bottom of every page on the site.
2. nav :is used to contain the major navigational blocks on the site such as the primary site navigatio.
3. article : element acts as a container for any section of a page that could stand alone and potentially be syndicated
4. section : element groups related content together, and typically each section would have its own heading
 
