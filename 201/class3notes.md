## Class 3 Notes

When should you use an unordered list in your HTML document?
When order doesn't matter or no numerical ordering. Typically for a circle, disc, square or triangle.

How do you change the bullet style of unordered list items?
By nesting the unordered list items

When should you use an ordered list vs an unorder list in your HTML document?
When order matters. An ordered list when there is an order or priority. A unordered list when there is no order or meaning to the list.

Describe two ways you can change the numbers on list items provided by an ordered list?
type
Sets the numbering type:

a for lowercase letters
A for uppercase letters
i for lowercase Roman numerals
I for uppercase Roman numerals
1 for numbers (default)

For example:
<ol type="i">
  <li>Introduction</li>
  <li>List of Grievances</li>
  <li>Conclusion</li>
</ol>

<p>Finishing places of contestants not in the winners' circle:</p>

<ol start="4">
  <li>Speedwalk Stu</li>
  <li>Saunterin' Sam</li>
  <li>Slowpoke Rodriguez</li>
</ol>

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Margin is the skeleton man who tries to stretch out and take up as much space as he can. While padding is the muscle man who fills up as much space as he can. The roll of padding is to sit around the content as white space; size it up. While margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements.

List and describe the four parts of an HTML elements box as referred to by the box model.

* Content Box: is the area where content is displayed. You can use inline-size, block-size, width, and height.
* Padding box: is the padding around the conetent as white space.
* Border box: is the border that wraps the content and any padding.
* Margin box: is the outermost layer, wrapping the content, padding, and border in whitespace between this box and other elements.

What data types can you store inside of an Array?
Strings and Numbers
Objects and arrays

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

 Yes it is a valid array. 
 console.log(people[0]);
 returns 'pete', 32, 'librarian', null

 List five shorthand operators for assignment in javascript and describe what they do.
Assignment x = f() x = f()
Addition assignment x += f() x = x + f() 
Subtraction assignment x -= f() x = x - f()
Multiplication assignment x *= f() x = x * f()
Division assignment x /= f() x = x / f()
Remainder assignment x %= f() x = x % f()
Exponentiation assignment x **= f() x = x ** f()
Left shift assignment x <<= f() x = x << f()
Right shift assignment x >>= f() x = x >> f()
Unsigned right shift assignment x >>>= f() x = x >>> f()
Bitwise AND assignment x &= f() x = x & f()
Bitwise XOR assignment x ^= f() x = x ^ f()
Bitwise OR assignment x |= f() x = x | f()
Logical AND assignment x &&= f() x && (x = f())
Logical OR assignment x ||= f() x || (x = f())
Nullish coalescing assignment x ??= f() x ?? (x = f())

Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

false because false makes the expression (read left to right) stay false.

Describe a real world example of when a conditional statement should be used in a JavaScript program.
Deciding if to get up and eat breakfast or to stay in bed and rest.

Give an example of when a Loop is useful in JavaScript.
A loop is useful when you want to ask something repeatedly until you get the right answer. Like as if this will complete your order at a drive through so you can pull forward and pay for your meal.

[Back Home](../reading-notes/README.md)