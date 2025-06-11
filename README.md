# CSE-264-Homework-Assignment-6-HTML-Outline-Generator-solved

Download Here: [CSE 264 Homework Assignment 6 – HTML Outline Generator solved](https://jarviscodinghub.com/assignment/homework-assignment-6-html-outline-generator-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

You will create a Javascript application that, when embedded on an HTML page, will traverse the DOM tree for the page and create an outline
representing the structure of the html page and embed that outline at the bottom of the page.
Collaboration Reminder
* You must submit your own work.
* In particular, you may not:
– Show your code to any of your classmates.
– Look at or copy anyone else’s code.
– Copy material found on the Internet.
– Work together on an assignment
Example
The following page:

Hello World


when loaded into the browser will display something close to the following at the bottom of the page:
* html
* head
* body
* h1
* text(Hello World)
* script src(”https://code.jquery.com/jquery-2.1.0.min.js”) type(”text/javascript”)
* script src(”outline.js”) type(”text/javascript”)
Instructions
1. Start by creating a new HTML5 project in NetBeans.
2. Delete the index.html page and copy your personal web site page into the project, renaming it index.html.
3. Create a file, outline.js to hold all of your Javascript code and insert it in index.html using a script tag as shown above. Also include the
jquery file (latest version) just above your code.
4. In outline.js:
(a) Use jQuery to handle all events and DOM traversal and manipulation.
(b) Use $(document).ready(…) to set a function to fire on page load and build and insert the outline in the page.
(c) Write a recursive function that will traverse the DOM tree for the page – from the html element down to the leaves (elements with no
child nodes). I suggest using a postorder traversal of the tree and building the outline from the leaves up. Once the entire outline is
created, append it to the body of the page. The outline should be implemented as a

with nested unordered lists for each level in
 

the tree. Don’t create the outline by building up a big string of html tags and then convert it to a DOM object; instead, create the DOM
 

objects using jQuery as you go along and use the jQuery methods to put them together (this will require a bit of jQuery research).
 

5. Zip up the whole project and upload to Coursesite.
