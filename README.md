
<b>HTML

As mentioned in the introduction, HTML is the skeleton of a webpage. HTML documents consist of tags and within them is the information. All HTML documents must start with a <!DOCTYPE> declaration.The declaration is not an HTML tag. It is information to the browser about what document type to expect.<!DOCTYPE html> - This is the declaration for HTML 5

The following are some basic html tags:-
```xml
 <html>.....</html>
```
- Starts the actual program. This tag encloses the entire HTML document, the head and body tags all are within this
```xml
<head>.....</head>
```
- Contains information like links to stylesheets[CSS files], bootstrap, meta tags and title
```xml
<title>.....</title>
```
- This tag is within the head tag and displays its content in the tab name.
```xml
<body>....</body>
```
- This tag contains the majority of the code and all code for the user interface of the webpage.
```xml
<h1>....</h1>
```
   - This tag gives a heading which is bold and large
```xml
<p>....</p> 
```
- This tag is used to add a paragraph to the html document. This also adds some blank spacing above and below the paragraph.
```xml
<br> 
```
- The br tag does not require a closing tag (</br> is wrong). This represents a line break in the text. The text after this tag begins front the next line at the margin.

Now let us test all these tags and create a sample webpage. You can use any code editor supporting html, css and javascript for this. I will be using Visual Studio Code for editing and Google Chrome as the browser for viewing the web pages.

SAMPLE CODE

RESULT:

Now let us learn more about these tags.

HEAD
```xml
<title>
```
-  This only affects the top tab bar. The content with these tags is what appears as the tab name.

Example:-\
![](https://lh5.googleusercontent.com/T3bJ-Zkk3HSxLuUuAmg-KF7BzWXLwaI-MfsUqTY0nyvGGBgXDmyfwQxjAvT6aqojfdI2KzPgvgzjp_H43qyNh1MokCGhN0-KYhcAkEQKS1jjuRk-DO4HyL48bfyOauTOMcVsDPON=s0)

-   Meta tags - The meta tag defines metadata about an HTML document. This data isn't shown on the page but it is used by browsers and search engines to index websites better. It is typically used to specify character set, page description, keywords, author of the document, and viewport settings.

-   Keywords: This helps search engines like Google to recommend websites according to relevance when someone searches something on google. The more relevant the keywords are, the higher a website is shown in search. Google also checks other details beside keywords. 
```xml
        <meta name="keywords" content="food, travel, adventure">
```      
-   Description: This too helps search engines recommend websites most relevant to the searched terms.
```xml
        <meta name="description" content="Travel and lifestyle blog">
```
-   Viewport: The screen varies from one device to the other, like a phone's screen is much smaller compared to that of  a desktop. Having a desktop optimized site on a mobile device will make its content miniscule and difficult to read. To avoid this viewport meta tag is used to optimize your website according to the user's screen size.
```xml
<meta name="viewport" content="width=device-width, initial-scale=1.0"> .
```
The initial scale can be altered to customize the initial zoom level when the website first loads.width=device-width  sets the width of the page to follow the screen's width.

![](https://lh3.googleusercontent.com/wtWLOgCT0DUiytUK3mxDx47aF0fzf7_0z65T2vppP6Cc0LvT8WvZ9If0WYG6qfEX9aNzJ7v3oK49-yeXDtas8IC8UYkeHNxrq8QWMevEeD52AIgjNv8AvPGKI_ha6-vujWHAULKX=s0)![](https://lh6.googleusercontent.com/g6oZqgkqpuMbvWq3fwoXWWbrOlb6uy93WipBlBY-c-JrdPdlDMkXPb46GafUDhU4xmJ6d53fuDWERdikNMU-W5AMZyue79X-pIgxd5foHPZQW6TbPp2DgumcJpK5Gfj8rtbCwi8g=s0)

           Without viewport                           With viewport

Source:w3schools.com

-   Links - Link tags are used to link stylesheets, fonts, images etc.

A basic link tag consists of the following attributes:-

-   rel - relationship(optional)

-   type - media type(optional)

-   href - to specify the location of the linked document (mandatory)

Syntax: <link rel = "stylesheet" type= "text/css" href = "style.css">

BODY

-   Header - These are used to display text as a heading.There are six header tags - \<h1>,\<h2>,\<h3>,\<h4>,\<h5>,\<h6> (in decreasing order of font size).\
![](https://lh6.googleusercontent.com/9JEWtWt-36rAy1QqhAmABHH0aMNWCuY5D4T1K800pQsG5VOweRq7xzYFs16QNCaUjwJ8g-xKfoL1dO0-8IJ67cFX63z07yFcXB6R4l0VvLDt0UV8zlH9MXlMCbJWfGE0GALDZMZO=s0)

-   Images - We can also add images to our website to make it more appealing or to convey information. 
```xml
<img src="images/pizza.jpg" alt= "food" width= "200" height = "300">
```
Attributes:-

-   src - This is the location of the image

-   alt - An alternate text for the image, if the image can't be displayed

-   width - Sets width of image

-   height - Sets height of image 

-   Paragraph and line break ( \<p>...\</p> & \<br>) - Discussed before.

-   Links to websites \<a>- The 'a href' tag can be used to link text to other webpages. We do not use the <link> tag as in the header for linking web pages instead we use this. The  href = ".." part specifies the webpage that is to be linked. The text between the <a> open tag and </a>close tag is what appears on the webpage, when we click on this text it will redirect us to the specified link.
```xml
<a href ="https://www.example.com(https://www.example.com/)">Click here!</a>
```
If we want the link to open in a new tab we have to add "target= _blank" after the href part.

-   Marquee-  HTML marquee is a scrolling piece of text displayed either horizontally across or vertically down your webpage depending on the attributes. 
```xml
<marquee> Example scrolling text </marquee>
```
Attributes (all attributes follow the syntax  \<marquee  attributename = " value">...\</marquee>):

-   direction- This specifies the direction the marquee should. scroll in, can be up,down, left or right.

-   height, width- Used to set dimensions.

-   bgcolor - Specifies the background color of the marquee.

-   scrolldelay- Specifies how long to delay between each appearance.

-   scrollamount- Specifies the speed of scrolling.(in numbers)

-   behaviour- Alters the movement of marquee.Can be 'slide', 'scroll', ' alternate'.

-   loop- Specifies how many times the marquee will loop. The default is infinite.

-   Styling text - We can style text in the following ways:-

-   Bold- The \<strong>...\</strong> or \<b>...\</b> tags can be used to bold text.

-   Italics- The \<i>...\</i> or \<em>...\</em> tags can be used to italicize text.

-   Underline- The \<u>...\</u> tag can be used to underline text

-   List tags - HTML allows us to form lists, there are two kinds:-

-   Ordered List \<ol>- These lists are ordered in the sense that each list item is numbered. Each list member is enclosed with in \<li> tags

 ![](https://lh5.googleusercontent.com/K68mY-ZyuLZMf969q9790YFU8wxcdNR8Vzj3Qqbdozpg1HOj2ktcOVes6zj73WXar3TNix6ZhE0bh5tXuc_BJfP8IbP6dapF_n45m6hIbPqk8AaGGESKi_zMSYXMiWJY72deoi22=s0)

-   Unordered List\<ul>- These are unordered lists, and have bullets before each list item.\
![](https://lh5.googleusercontent.com/pNaBLFWOVGa3Wtoa-PbwunpRLnt4qnRtKXIHHiJRhtHGj7t8aMSfQFKKujvyEPQNvVL9Bj0ehptjFCGBnwimqDjiiFVzZSQ37NGRd9x6ysD8CBnHm6l-wTag_ssCoTaxwsbHEsrJ=s0)

-   Div tags \<div>- These are divisions within the body, which help us divide the code into blocks. This is very useful in styling your web pages using CSS, as we can call these classes in CSS by their name and customize the content of that div. Divs can be inside of divs too. Divs can have a class name or/and an id, which can be used to call it.

-   iframe - An iframe displays an HTML document or a webpage within an HTML document.This is used to show preview of other websites in another webpage, often it is used to display videos from websites or even maps.

Attributes:-

-   Src- The src attribute is used to link the webpage that is to be displayed. Syntax:  src= "examplesite.com"

-   Dimensions- The height and width tags can be used to specify dimensions.![](https://lh6.googleusercontent.com/BTKJE9ZtiO_HTsKHRSZlTjUt_51UHiVKk7aWUp19t5pVVt2GVZB0r9ZQpgt6-f4n25p0TWz-xMejl5_BGoeK5MVtjJT9BBhe17U3fG11kFUegyK20fArHNgt_CB9Rl2cEgLE84C8=s0)

-   Comments - Comments are ignored by the browser and can be in simple text. They are for others or you to understand what the code is about when looking at it.
```xml
<!-- This is a comment.The browser will ignore this.-->
```
-   Style - The \<style>...\</style> tag can be used to write CSS within an HTML 5 document.

-   Script- The \<script>...\</script> tag can be used to write Javascript within an HTML 5 document or link to JS files.
