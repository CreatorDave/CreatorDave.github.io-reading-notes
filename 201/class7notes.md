## Explain why we need domain modeling.
We need domain modeling for object-oriented programming

This is object-oriented programming in JavaScript at its most fundamental level.

The new keyword instantiates (i.e. creates) an object.
The constructor function initializes properties inside that object using the this variable.
The object is stored in a variable for later use.

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

## Why should tables not be used for page layouts?
because CSS support across browsers used to be terrible; table layouts are much less common nowadays, but you might still see them in some corners of the web.
Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users.
Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.
Tables are not automatically responsive: When you use proper layout containers (such as <header>, <section>, <article>, or <div>), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

## List and describe 3 different semantic HTML elements used in an HTML <table>.
<th> element ('th' stands for 'table header').
<tr>
<td>

## What is a constructor and what are some advantages to using it?
A constructor is just a function called using the new keyword. When you call a constructor, it will:

create a new object
bind this to the new object, so you can refer to this in your constructor code
run the code in the constructor
return the new object.

Constructors, by convention, start with a capital letter and are named for the type of object they create. So we could rewrite our example like this:

function Person(name) {
  this.name = name;
  this.introduceSelf = function () {
    console.log(`Hi! I'm ${this.name}.`);
  };
}

To call Person() as a constructor, we use new:

const salva = new Person("Salva");
salva.name;
salva.introduceSelf();

const frankie = new Person("Frankie");
frankie.name;
frankie.introduceSelf();

## How does the term this differ when used in an object literal versus when used in a constructor?
bind this to the new object, so you can refer to this in your constructor code

## Explain prototypes and inheritance via an analogy from your previous work experience

NOTE: This is a very common front end developer interview question
Prototypes are like an extra wrench you can use to unscrew a nut when you've arched your wrench.

Explain prototypes and inheritance via an analogy from your previous work experience.

Inheritance is when you get assigned to a new bomblift. The old problems keep coming along with it.

NOTE: This is a very common front end developer interview question


[Back Home](../reading-notes/README.md)