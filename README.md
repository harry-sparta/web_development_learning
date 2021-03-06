# Web Development Record
Resource link: https://www.w3schools.com/whatis/default.asp

## Table of contents
1.) [What is HTTP?](##http)\
2.) [HTML Basics](##html)



## <a name="http"> What is HTTP? </a>
**HTTP** = Hyper Text Transfer Protocol
**WWW** = World Wide Web
**HTML** = Hyper Text Markup Language

WWW is about communication between web clients and web servers.

**Clients** = e.g. browsers (Chrome, Safari, Edge).
**Servers** = e.g. computers in the cloud

Communication requests and responses:
- A client (a browser) sends an HTTP request to the web
- An web server receives the request
- The server runs an application to process the request
- The server returns an HTTP response (output) to the browser
- The client (the browser) receives the response

Typical HTTP circle:
- The browser requests an HTML page. The server returns an HTML file.
- The browser requests a style sheet. The server returns a CSS file.
- The browser requests an JPG image. The server returns a JPG file.
- The browser requests JavaScript code. The server returns a JS file
- The browser requests data. The server returns data (in XML or JSON).


## <a name="html"> HTML Basics </a>
**Hyper Text Markup Language** is a standard markup language for web pages and HTML elements are represented by <> tags.

### HTML Elements
- Heading: ````<h1> Heading name </h1>````
- Paragraph: ````<p> Paragraph name <p>````

### HTML Attributes
HTML elements can have attributes. It provides additional information about the element. Attributes come in **name/value** pairs like **charset="utf-8"**

### Common HTML elements used
HTML elements are the building blocks of HTML pages.

- ````<!DOCTYPE html>```` declaration defines this document to be HTML5
-````<html>```` element is the root element of an HTML page
- ````lang```` attribute  defines the language of the document
- ````<meta>```` element contains meta information about the document
- ````charset```` attribure defines the character set used in the document
- ````<title>```` element specifies a title for the document
- ````<body>```` element contains the visible page content
- ````<h1>```` element defines a large heading. Goes from ````<h1>````` to ````<h6>````
- ````<p>```` element defines a paragraph
- ````<a>```` element defines links. A link's destination is specified in the ````href=""```` attribute. e.g. ````<a href="web-link">text description for the hyperlink</a>````
- ````<img>```` element defines images. The source file ````src````, alternative text ````alt````, ````width````, and ````height```` are provided as **attributes**. eg. ````<img src="image-file", alt="alternative-text", style="width:100px;height:100px"````>

### HTML Documents
- must start with a document type declaration: ````<!DOCTYPE html>````.
- begins with ````<html>```` and ends with ````</html>````.
- **visible part** of the HTML document is between ````<body>```` and ````</body>````.

### General HTML Document Structure
````
<html>
  <head>
    <title>Page title</title>
    </head>
  <body>  # Browser will only display what is in the BODY <body start>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body> # Browser will only display what is in the BODY <body end>
</html>
````
