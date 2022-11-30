# Class 2 notes

Why is it important to use semantic elements in our HTML?
Semantics are relied on for meaning and function of the structure of the website. It gives meaning to the function of the website. This gives the correct meaning, function, or appearance.

How many levels of headings are there in HTML?
6
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

What are some uses for the <sup> and <sub> elements?
<sup> is for superscript and appears a half a character above the normal line and is sometimes rendered in a smaller font. You can use this for powers or sections in a document.
<sub> is for subscript and appears half a character below the normal line and is sometimes rendered in a smaller font. You can use this for bases or sections in a document.

When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
The abbr element represents an abbreviation or acronym, optionally with its expansion. The title attribute may be used to provide an expansion of the abbreviation. The attribute, if specified, must contain an expansion of the abbreviation, and nothing else.

What are ways we can apply CSS to our HTML?
Inline, internal, and external

Why should we avoid using inline styles?
Inline has parse precedence. Meaning the priority is higher and will supercede the rest.

What is representing the selector? h2
Which components are the CSS declarations? color, padding
Which components are considered properties? black, 5px

   h2 {
     color: black;
     padding: 5px;
   }

What data type is a sequence of text enclosed in single quote marks?
String

List 4 types of JavaScript operators.
<, >, <=, >=

Describe a real world Problem you could solve with a Function.
Taking someone's order at Taco Bell.

An if statement checks a _conditional_ and if it evaluates to _true__, then the code block will execute.

What is the use of an else if?
Logic to check for other conditions.

List 3 different types of comparison operators.
<, >, >=



## JavaScript

JavaScript is a **loosely typed** and **dynamic** language

-Loosely type - we don't need to know the type of data before declaring a vraiable
-Dynamic - you can change the type after it has been declared

- 
let cat;

- 'cat = 3;'

-'cat = 'meow';`

## Data Types

### Strings

- sequence of characters used to represent text. Written using single quotes.
- `'hello'`, `'

### Numbers

- numeric data type
- full numbers, decimals, negatices

### Boolean

- logical data types
-true // false
- truthy // falsy

### Undefined

- it has not been deifined yet

### Null

- has been defined but defined as none

Numbers
0 - is the only falsey value
any other number is considered truthy

Strings 
'' - is the only falsey value
any other string is considered truthy

Comparison operators - what are some examples?
>=, <=, < , >
!== strictly not equal - this is our world
!= loosely not equal - comparative not equal - not out world!
=== strictly equal - THis is our world
== loosely/Comparative equal - not out world


[Back Home](../reading-notes/README.md);