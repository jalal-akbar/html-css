# html-css

# Introduction
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

# Basic
- # HTML Documents
- All HTML documents must start with a document type declaration: <!DOCTYPE html>.
- The HTML document itself begins with <html> and ends with </html>.
- The visible part of the HTML document is between <body> and </body>.
- # The <!DOCTYPE> Declaration
- The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.
- It must only appear once, at the top of the page (before any HTML tags).
- The <!DOCTYPE> declaration is not case sensitive.
- The <!DOCTYPE> declaration for HTML5 is:
```
<!DOCTYPE html>
```
- # HTML Headings
- HTML headings are defined with the <h1> to <h6> tags.
- <h1> defines the most important heading. <h6> defines the least important heading:
```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```
- # HTML Paragraphs
- HTML paragraphs are defined with the <p> tag:
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
- # HTML Links
- HTML links are defined with the <a> tag:
```
<a href="https://www.w3schools.com">This is a link</a>
```
- The link's destination is specified in the href attribute. 
- Attributes are used to provide additional information about HTML elements.
- You will learn more about attributes in a later chapter.
- # HTML Images
- HTML images are defined with the <img> tag.
- The source file (src), alternative text (alt), width, and height are provided as attributes:
```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

# Elements
- The HTML element is everything from the start tag to the end tag:
<tagname>Content goes here...</tagname>

# Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"
- Example
```
<a href="https://www.w3schools.com">Visit W3Schools</a>
<img src="img_girl.jpg">
<img src="img_girl.jpg" width="500" height="600">
<img src="img_girl.jpg" alt="Girl with a jacket">
```
