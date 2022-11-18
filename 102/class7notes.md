# Control Flow

The control *flow* is the order in which the computer executes statements in a script.

Code is run in oreder from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, with loops and conditionals.

A conditional statement is *if* and *else* statements. These statements accompany a function that gives a logic for the computer to evaluate based on the user's response.

A function looks like this:
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

You type function then the name of the function. Typically something you think would be appropriate for the logic being determined. Then you have parameters which are the arguments the function will determine. Following this is the code along with conditionals or loops to determine how long you want the code to execute the logic.

Within the code is a function **return** that allows the function to complete and produce a value or output. You will need to console.log this function to see what function produced.

Here's an example:
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

console.log(myFunction)

Don't forget that in JavaScript you use Camelcase to write out the functions. This makes it easier to understand and recognize the functions. Camelcase works by lowercasing the first word and uppercasing the subsequent words in the function. Much like *myFunction*

In JavaScript you have Operators.

Examples:
=
+
-
/
%
&&
||
!=
!==
<
>
>=
<=
?
>
!

These allow you to do mathematical and logic calculations in JavaScript.

There's also Type Operators like
typeof
instanceof

These return the type of variable and returns true if an object is an instance of an object type.




[Back Home](../reading-notes/README.md)
