![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png)


# **Learn_basic_HTML**

   - HTML stands for Hyper Text Markup Language
   - HTML describes the structure of a Web page
   - HTML consists of a series of elements
   - HTML elements tell the browser how to display the content
   - HTML elements are represented by tags
   - HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
     Browsers do not display the HTML tags, but use them to render the content of the page

### First Program

 
      <!DOCTYPE html>
      <html>
      <head>
      <title>Page Title</title>
      </head>
      <body>

      <h1>My First Heading</h1>
      <p>My first paragraph.</p>

      </body>
      </html>
 
 
   #### *Program Explained*
   - The <!DOCTYPE html> declaration defines this document to be HTML5
   - The `<html>`element is the root element of an HTML page
   - The `<head>`element contains meta information about the document
   - The `<title>`element specifies a title for the document
   - The `<body>`element contains the visible page content
   - The `<h1>`element defines a large heading
   - The `<p>`element defines a paragraph

   #### *HTML Tags*
   - HTML tags are element names surrounded by angle brackets:
   ###### `<tagname>`content goes here...`</tagname>`
   
   
   - HTML tags normally come in pairs like `<p>`and`</p>`.
   - The first tag in a pair is the start tag, the second tag is the end tag.
   - The end tag is written like the start tag, but with a forward slash inserted before the tag name.
   
   
### The `<!DOCTYPE>` Declaration
- The `<!DOCTYPE>` declaration represents the document type and helps browsers to display web pages correctly.
- It must only appear once, at the top of the page (before any HTML tags).
- The `<!DOCTYPE>` declaration is not case sensitive.
- The `<!DOCTYPE>` declaration for HTML5 is:
   ### **`<!DOCTYPE>`**


### Year 	Version
> - 1989 Tim Berners-Lee invented www
> - 1991 Tim Berners-Lee invented HTML
> - 1993 Dave Raggett drafted HTML+
> - 1995 HTML Working Group defined HTML 2.0
> - 1997 W3C Recommendation: HTML 3.2
> - 1999 W3C Recommendation: HTML 4.01
> - 2000 W3C Recommendation: XHTML 1.0
> - 2008 WHATWG HTML5 First Public Draft
> - 2012 WHATWG HTML5 Living Standard
> - 2014 W3C Recommendation: HTML5
> - 2016 W3C Candidate Recommendation: HTML 5.1
> - 2017 W3C Recommendation: HTML5.1 2nd Edition
> - 2017 W3C Recommendation: HTML5.2

## HTML Documents

  - All HTML documents must start with a document type declaration: <!DOCTYPE html>.
  - The HTML document itself begins with <html> and ends with </html>.
  - The visible part of the HTML document is between <body> and </body>. 
  
        <!DOCTYPE html>
        <html>
        <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
        </body>
        </html> 
## HTML Headings

### HTML headings are defined with the <h1> to <h6> tags.
#### <h1> defines the most important heading. <h6> defines the least important heading: 
