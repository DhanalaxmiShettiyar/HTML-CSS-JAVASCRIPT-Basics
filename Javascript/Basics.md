<Javascript>
=> Acts as a behavioural part of a web page.

<Javascript can change HTML content>
> Method --> getElementById()
             Here, it finds an HTML element (with id="demo") and changes the element content (innerHTML) to the updated string.
        Example - document.getElementById('demo').innerHTML = 'Hello Javascript!' 

** JavaScript accepts both double and single quotes **

JavaScript Can Change HTML Styles (CSS)
--> document.getElementById("demo").style.fontSize = "35px";

JavaScript Can Hide HTML Elements
--> document.getElementById("demo").style.display = "none";

JavaScript Can Show HTML Elements
--> document.getElementById("demo").style.display = "block";

<The <script> Tag>
In html, Js code is inserted between <script> and </script> tags
Example - 
<script> 
document.getElementById("demo").innerHTML = "Javascript";

<Javascript Functions>
-> A function is block of Javscript code, that can be executed when 'called' or invoked.
For example, a function can be called when an event occurs, like when the user clicks a button.
Javascript in <head> or <body>
--> Scripts can be placed in the <body> or in the <head> section of an HTML page, or in both.

** Javascript in <head>
Javascript in <body> **

<External Javascript>
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


<Javascript Output>
--> 4 js display properties:
- Writing into an HTML element, using innerHTML.
- Writing into the HTML output using document.write().
- Writing into an alert box, using window.alert().
- Writing into the browser console, using console.log().

Using innerHTML
--> To access an HTML element, JavaScript can use the document.getElementById(id) method.
The id attribute defines the HTML element. The innerHTML property defines the HTML content.

Using document.write()
--> For testing purposes, it is convenient to use document.write()

** Using document.write() after an HTML document is loaded, will delete all existing HTML. **

Using Window.alert()
--> You can use an alert box to display data.
In JavaScript, the window object is the global scope object, that means that variables, properties, and methods by default belong to the window object. This also means that specifying the window keyword is optional.

Using console.log()
--> For debugging purposes, you can call the console.log() method in the browser to display data.

<Javascript print>
--> JavaScript does not have any print object or print methods.
You cannot access output devices from JavaScript.
The only exception is that you can call the window.print() method in the browser to print the content of the current window.

<Javascript Statements>
--> JavaScript statements are composed of:
Values, Operators, Expressions, Keywords, and Comments.
This statement tells the browser to write "Hello Dolly." inside an HTML element with id="demo".
- Example
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3

<Javascript Programs>
--> A computer program is a list of "instructions" to be "executed" by a computer.
In a programming language, these programming instructions are called statements.
A JavaScript program is a list of programming statements. In HTML, JavaScript programs are executed by the web browser.

<Semicolons>
--> Semicolons separate JavaScript statements.
Add a semicolon at the end of each executable statement:
Examples
let a, b, c;  // Declare 3 variables
a = 5;        // Assign the value 5 to a

<Javascript White Space>
--> JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

<JavaScript Line Length and Line Breaks>
--> For best readability, programmers often like to avoid code lines longer than 80 characters.
If a JavaScript statement does not fit on one line, the best place to break it is after an operator.

<JavaScript Code Blocks>
--> JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.
The purpose of code blocks is to define statements to be executed together.
One place you will find statements grouped together in blocks, is in JavaScript functions.

<Javascript Keywords>
--> JavaScript statements often start with a keyword to identify the JavaScript action to be performed.
Some of the keywords are:
1) var - declares a variable
2) let - declares a block variable
3) const - declares a block constant
4) if - marks a block of statments to be executed on a condition.
5) switch - marks a block of statements to be executed in different cases
6) for - marks a block of statements to be executed in a loop.
7) function - declares a function.
8) return - exists a function.
9) try - implements error handling to a block of statements.

** JavaScript keywords are reserved words. Reserved words cannot be used as names for variables. **

<Javascript Values>
--> The JavaScript syntax defines two types of values:
- Fixed values / JavaScript Literals : Fixed values are called Literals.
Rules - 
1. Numbers are written with or without decimals:
10.50
1001
2. Strings are text, written within double or single quotes:
"John Doe"
'John Doe'

- Variable values / JavaScript Variables : Variable values are called Variables.
* In a programming language, variables are used to store data values.
* JavaScript uses the keywords var, let and const to declare variables.
* An equal sign is used to assign values to variables.
* Example : In this example, x is defined as a variable. Then, x is assigned (given) the value 6:
let x;
x = 6;

<Javascript Operators>
--> Js uses:
1) Arithmetic operators( + - * /) - compute values.
2) Assignment operators( = ) - assign values to variables.

<Javascript Expressions>
--> An expression is a combination of values, Variables and operators which computes to value.
The computation is called an evaluation. 
Example: 5 * 10 evaluates to 50.
"John" + " " + "Doe", evaluates to "John Doe"

<JavaScript Comments>
--> Code after double slashes // or between /* and */ is treated as a comment.
Example - 
let x = 5;   // I will be executed
// x = 6;   I will NOT be executed

<JavaScript Identifiers / Names>
--> Identifiers are JavaScript names.
Identifiers are used to name variables and keywords, and functions.
Rules - A JavaScript name must begin with:
1) A letter (A-Z or a-z)
2) A dollar sign ($)
3) Or an underscore (_)

** JavaScript is Case Sensitive **

<JavaScript and Camel Case>
--> 
- Hyphens: first-name, last-name, master-card, inter-city.
Hyphens are not allowed in JavaScript. They are reserved for subtractions.

- Underscore: first_name, last_name, master_card, inter_city.

- Upper Camel Case (Pascal Case): FirstName, LastName, MasterCard, InterCity.

- Lower Camel Case: JavaScript programmers tend to use camel case that starts with a lowercase letter:
firstName, lastName, masterCard, interCity.

** JavaScript uses the Unicode character set. **

<JavaScript Comments>
--> JavaScript comments can be used to explain JavaScript code, and to make it more readable.
JavaScript comments can also be used to prevent execution, when testing alternative code.
1) Single Line Comments - starts with //
2) Multi-line Comments - starts with /* and ends with */


<Javascript Variables>
--> variables are containers for storing data(storing data values)
4 Ways to Declare a JavaScript Variable:
1) Using var
2) Using let
3) Using const
4) Using nothing

var -> function scope / global scope
let & const -> block scope

<Javascript identifiers>
--> All JavaScript variables must be identified with unique names.
These unique names are called identifiers.
Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

Rules
- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter
- Names can also begin with $ and _
- Names are case sensitive (y and Y are different variables)
- Reserved words (like JavaScript keywords) cannot be used as names

** The "equal to" operator is written like == in JavaScript. **

<Declaring a JavaScript Variable>
--> Creating a variable in JavaScript is called "declaring" a variable.
You declare a JavaScript variable with the var or the let keyword.
Ex - let carName;
After the declaration, the variable has no value (technically it is undefined)
defining a variable after its declaration is called definition.
Ex - carName = "Volvo";

<Javascript Concatenation>
Ex - let x = "John" + " " + "Doe"; // John Doe
     let x = "5" + 2 + 5; // 57

<JavaScript Dollar Sign $>
--> Since JavaScript treats a dollar sign as a letter, identifiers containing $ are valid variable names:
Example
let $ = "Hello World";
we use it as an alias for the main function in a JavaScript library.

<JavaScript Underscore (_)>
Since JavaScript treats underscore as a letter, identifiers containing _ are valid variable names:
Example
let _lastName = "Johnson";
It is to use it as an alias for "private (hidden)" variables.

<Javascript let keyword>
* The let keyword was introduced in ES6 (2015).
* Variables defined with let cannot be Redeclared.
* Variables defined with let must be Declared before use.
* Variables defined with let have Block Scope.

<Javascript const keyword>
* The const keyword was introduced in ES6 (2015).
* Variables defined with const cannot be Redeclared.
* Variables defined with const cannot be Reassigned.
* Variables defined with const have Block Scope.

<var Hoisting>
--> Variables defined with var are hoisted to the top and can be initialized at any time.
Meaning: You can use the variable before it is declared.
Example:
carName = "Volvo";
var carName;

<let and const Hoisting>
--> Variables defined with let are also hoisted to the top of the block, but not initialized.
Meaning: Using a let variable before it is declared will result in a ReferenceError
Example : 
carName = "Saab";
let carName = "Volvo";
// ReferenceError: Cannot access 'carName' before initialization

<JavaScript Operators>
1) The assignment operator (=) assigns a value to a variable.
2) The addition operator (+) adds numbers.
3) The multiplication operator (*) multiplies numbers.
4) ** - Exponentiation (ES2016)
5) / - Division.
6) % - Modulus(Division Remainder)
7) ++ - Increment.
8) -- - Decrement

<JavaScript Assignment Operators>
--> Assignment operators assign values to JavaScript variables.
1) Assignment operator             =        :       x = y
2) Addition assignment operator    +=       :       x = x + y
3) -=       :       x = x - y
4) *=       :       x = x * y
5) /=       :       x = x / y
6) %=       :       x = x % y
7) **=      :       x = x ** y

<JavaScript String Operators>
--> The + operator can also be used to add (concatenate) strings.
Example 1 - 
let text1 = "John";
let text2 = "Doe";
let text3 = text1 + " " + text2;
o/p: John Doe

Example 2 -
let text1 = "What a very ";
text1 += "nice day";
o/p: What a very nice day

<Adding Strings and Numbers>
Example - 
let x = 5 + 5;
let y = "5" + 5;
let z = "Hello" + 5;
o/p : 
10
55
Hello5

<JavaScript Comparison Operators>
1) ==   equal to
2) ===  equal value and equal type
3) !=   not equal
4) !==  not equal value or not equal type
5) >    greater than
6) <    less than
7) >=   greater than or equal to
8) <=   less than or equal to
9) ?    ternary operator

<JavaScript Logical Operators>
1) &&	logical and
2) ||	logical or
3) !	logical not

<JavaScript Type Operators>
1) typeof	    Returns the type of a variable
2) instanceof	Returns true if an object is an instance of an object type

<JavaScript Bitwise Operators>
--> Bit operators work on 32 bits numbers.
"https://www.w3schools.com/js/js_operators.asp"
