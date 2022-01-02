Javascript
=> Acts as a behavioural part of a web page.

Javascript can change HTML content 
> Method --> getElementById()
             Here, it finds an HTML element (with id="demo") and changes the element content (innerHTML) to the updated string.
        Example - document.getElementById('demo').innerHTML = 'Hello Javascript!' 

** JavaScript accepts both double and single quotes

JavaScript Can Change HTML Styles (CSS)
--> document.getElementById("demo").style.fontSize = "35px";

JavaScript Can Hide HTML Elements
--> document.getElementById("demo").style.display = "none";

JavaScript Can Show HTML Elements
--> document.getElementById("demo").style.display = "block";

The <script> Tag
In html, Js code is inserted between <script> and </script> tags
Example - 
<script> 
document.getElementById("demo").innerHTML = "Javascript";

Javascript Functions
-> A function is block of Javscript code, that can be executed when 'called' or invoked.
For example, a function can be called when an event occurs, like when the user clicks a button.

Javascript in <head> or <body>
--> Scripts can be placed in the <body> or in the <head> section of an HTML page, or in both.

Javascript in <head>
Javascript in <body>

External Javascript
--> External scripts are practical when the same  code is used in many different web pages.

    JavaScript files have the file extension .js.
    To use an external script, put the name of the script file in the src (source) attribute of a <script> tag:
    Example
    <script src="myScript.js"></script>

External JavaScript Advantages
--> Placing scripts in external files has some advantages:
- It separates HTML and code
- It makes HTML and JavaScript easier to read and maintain
- Cached JavaScript files can speed up page loads

