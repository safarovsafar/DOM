# DOM
 DOM - "Document Object Model". It's a standardized way of representing the structure of a document
 (such as HTML) as a tree-like structure, where each node represents a part of the document, such as an
 element, attribute, text content, etc. DOM allows programs and scripts to access, manipulate, and
 update the content, structure, and styles of a web page. JavaScript is commonly used to interact with
 the DOM in web development, for tasks such as dynamically changing the content of a page or handling
 user events.


 ![alt text](<Screenshot 2024-11-07 150610-1.png>)


## DOM features
According to the Document Object Model (DOM for short), every HTML tag is an object. 
Subtags are "children" of the parent element. The text that is inside the tag is also an
 object.All these objects are available with JavaScript, we can use them to modify the page.
![alt text](<Screenshot 2024-11-07 150816-1.png>)

### InnerHtml
 innerHTML - this property completely provides an easy way
 replace the elementary element. For example, all requirements
 the element's body can be removed:
 The Style object represents
 an individual style statement.


 ### DOM Events
 HTML events are "things" that happen to HTML elements.
 When JavaScript is used in HTML pages, JavaScript can "react" on these events.
  An HTML event can be something the browser does, or
 something a user does.

 ###  onclick -The user clicks an HTML element


 ## DOM create element
  The JavaScript document.createElement() method allows you to create and return a 
new element (an empty Element node) with the specified tag name.
 1) createElement(elementName): Creates an html element whose tag is
 passed as a parameter. Returns the created element