## How would you describe an object to a non-technical friend you grew up with?
An object is a collection of data and functionality. Consisting of variables and functions. An object begins with defining and initializing a variable. 

const person = {}

Example:
[object Object]
Object { }
{ }

The value of an object member can be pretty much anything — in our person object we've got a number, an array, and two functions.

person.name;
person.name[0];
person.age;
person.bio();
person.introduceSelf();

An object is a container with various functions and data.

## What are some advantages to creating object literals?
An Object is a special type of value in JavaScript that can have connections with other values.

An Object Literal is an object value that you literally write in your program/app.

An Object Literal usually consists of a list of comma-separated name-value pairs (property:value), wrapped inside curly braces {}.

## How do objects differ from arrays?
Objects can hold functions and various forms of data. Arrays typically hold strings and numbers. Where an Array is a list a object is a variety of data and functions.

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

Bracket notation
Bracket notation provides an alternative way to access object properties. Instead of using dot notation like this:

person.age;
person.name.first;
Copy to Clipboard
You can instead use brackets:

person["age"];
person["name"]["first"];
Copy to Clipboard
This looks very similar to how you access the items in an array, and it is basically the same thing — instead of using an index number to select an item, you are using the name associated with each member's value. It is no wonder that objects are sometimes called associative arrays — they map strings to values in the same way that arrays map numbers to values.

 if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

'this.name' is dot notation with name being the method. 'this' is the current object that the code is being written inside.

## What is "this"?
You may have noticed something slightly strange in our methods. Look at this one for example:

introduceSelf() {
  console.log(`Hi! I'm ${this.name[0]}.`);
}
Copy to Clipboard
You are probably wondering what "this" is. The this keyword refers to the current object the code is being written inside — so in this case this is equivalent to person. So why not just write person instead?

Well, when you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create.

## What is the DOM?
The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.


The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

Briefly describe the relationship between the DOM and JavaScript.

JavaScript is used to access the DOM. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. The DOM is not part of the JavaScript language, but is instead a Web API used to build websites.

[Back Home](../reading-notes/README.md)[Back Home](../reading-notes/README.md)