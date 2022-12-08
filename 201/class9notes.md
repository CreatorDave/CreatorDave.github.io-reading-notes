## Why are forms so important in web development?
Forms allow users to enter data that is sent to a web server for processing and storage, or to be used by the client-side to immediately update the interface in some way.

## When designing a form, what are some key things to keep in mind when it comes to user experience?
The bigger your form, the more you risk frustrating people and losing users.

**Here are some references:**
Smashing Magazine has some good articles about forms UX, including an older but still relevant Extensive Guide To Web Form Usability article.
UXMatters is also a very thoughtful resource with good advice from basic best practices to complex concerns such as multipage forms.
https://www.smashingmagazine.com/2018/08/ux-html5-mobile-form-part-1/
<https://www.smashingmagazine.com/2011/11/extensive-guide-web-form-usability/>
<https://www.uxmatters.com/mt/archives/2012/05/7-basic-best-practices-for-buttons.php>


List 5 form elements and explain their importance.
<form>, <label>, <input>, <textarea>, and <button>

<form action="/my-handling-form-page" method="post">…</form>

This element formally defines a form. It's a container element like a <section> or <footer> element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes:

The action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
The method attribute defines which HTTP method to send the data with (usually get or post).

Associating a <label> with a form control, such as <input> or <textarea> offers some major advantages:

<label>
  Do you like peas?
  <input type="checkbox" name="peas" />
</label>

The label text is not only visually associated with its corresponding text input; it is programmatically associated with it too. This means that, for example, a screen reader will read out the label when the user is focused on the form input, making it easier for an assistive technology user to understand what data should be entered.
When a user clicks or touches/taps a label, the browser passes the focus to its associated input (the resulting event is also raised for the input). That increased hit area for focusing the input provides an advantage to anyone trying to activate it — including those using a touch-screen device.

The <input> HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The <input> element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.

The <textarea> HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.


The markup for our form is almost complete; we just need to add a button to allow the user to send, or "submit", their data once they have filled out the form. This is done by using the <button> element; add the following just above the closing </ul> tag:

<li class="button">
  <button type="submit">Send your message</button>
</li>

The <button> element also accepts a type attribute — this accepts one of three values: submit, reset, or button.

A click on a submit button (the default value) sends the form's data to the web page defined by the action attribute of the <form> element.
A click on a reset button resets all the form widgets to their default value immediately. From a UX point of view, this is considered bad practice, so you should avoid using this type of button unless you really have a good reason to include one.
A click on a button button does nothing! That sounds silly, but it's amazingly useful for building custom buttons — you can define their chosen functionality with JavaScript.

## How would you describe events to a non-technical friend?
Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.
It's like an alarm system that let's you know what's going on.

## When using the addEventListener() method, what 2 arguments will you need to provide?
the name of the event and a function to handle the event.

## Describe the event object. Why is the target within the event object useful?
a parameter specified with a name such as event, evt, or e. The target property of the event object is always a reference to the element the event occurred upon.

## What is the difference between event bubbling and event capturing?
Event bubbling describes how the browser handles events targeted at nested elements. Event capturing was Netscape's version of event bubbling

[Back Home](../reading-notes/README.md)