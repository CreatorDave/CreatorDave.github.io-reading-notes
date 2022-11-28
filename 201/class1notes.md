## HTTP

The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

### Poem

Shiny new stuff to look at
Here comes the new shiny stuff to look at
The shiny stuff is parsed 
That shiny stuff is packaged
Giving you the shiny stuff to bring home
So you can finally display that lawn gnome


## Describe how HTML, CSS, and JS files are “parsed” in the browser

The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

## How can you find images to add to a Website?
You can find images on the web like through unsplash or any open site. From there download the image or get the url address for the images. This allows you to take an image from the website and then place that image in a markdown, html, or JavaScript document.

## How do you create a String vs a Number in JavaScript?
A String is written in quotes whether single or double. While a number is written as an integer. Here is an example:

String This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks. 

let myVariable = 'Bob';

Number This is a number. Numbers don't have quotes around them. 

let myVariable = 10;

## What is a Variable and why are they important in JavaScript?

A variable is a container that is used to store a value. It's like a box that you can put anything into and take out when necessary.

## What is an HTML attribute?

Attributes contain extra information about the element that won't appear in the content. In this example, the class attribute is an identifying name used to target the element with style information.

An attribute should have:

A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
The attribute name, followed by an equal sign.
An attribute value, wrapped with opening and closing quote marks.

## Describe the Anatomy of an HTMl element

The anatomy of our element is:

The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
The content: This is the content of the element. In this example, it is the paragraph text.
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

Edit the line below in the "Editable code" area by wrapping it with the tags <em> and </em>. To open the element, put the opening tag <em> at the start of the line. To close the element, put the closing tag </em> at the end of the line. Doing this should give the line italic text formatting! See your changes update live in the Output area.

## What is the Difference between <article> and <section> element tags?

The <article> HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.

Usage notes
Each <article> should be identified, typically by including a heading (<h1> - <h6> element) as a child of the <article> element.
When an <article> element is nested, the inner element represents an article related to the outer element. For example, the comments of a blog post can be <article> elements nested in the <article> representing the blog post.
Author information of an <article> element can be provided through the <address> element, but it doesn't apply to nested <article> elements.
The publication date and time of an <article> element can be described using the datetime attribute of a <time> element.

The <section> HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.

Usage notes
As mentioned above, <section> is a generic sectioning element, and should only be used if there isn't a more specific element to represent it. As an example, a navigation menu should be wrapped in a <nav> element, but a list of search results or a map display and its controls don't have specific elements, and could be put inside a <section>.

Also consider these cases:

If the contents of the element represent a standalone, atomic unit of content that makes sense syndicated as a standalone piece (e.g. a blog post or blog comment, or a newspaper article), the <article> element would be a better choice.
If the contents represent useful tangential information that works alongside the main content, but is not directly part of it (like related links, or an author bio), use an <aside>.
If the contents represent the main content area of a document, use <main>.
If you are only using the element as a styling wrapper, use a <div>. An unwritten rule is that a <section> should logically appear in the outline of a document.
To reiterate, each <section> should be identified, typically by including a heading (<h1> - <h6> element) as a child of the <section> element, wherever possible. See below for examples of where you might see a <section> without a heading.

## What Elements does a “typical” website include?

header: <header>.
navigation bar: <nav>.
main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
sidebar: <aside>; often placed inside <main>.
footer: <footer>.


<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />

    <title>My page title</title>
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One"
      rel="stylesheet" />
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <!-- Here is our main header that is used across all the pages of our website -->

    <header>
      <h1>Header</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Our team</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contact</a></li>
      </ul>

      <!-- A Search form is another common non-linear way to navigate through a website. -->

      <form>
        <input type="search" name="q" placeholder="Search query" />
        <input type="submit" value="Go!" />
      </form>
    </nav>

    <!-- Here is our page's main content -->
    <main>
      <!-- It contains an article -->
      <article>
        <h2>Article heading</h2>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Donec a diam
          lectus. Set sit amet ipsum mauris. Maecenas congue ligula as quam
          viverra nec consectetur ant hendrerit. Donec et mollis dolor. Praesent
          et diam eget libero egestas mattis sit amet vitae augue. Nam tincidunt
          congue enim, ut porta lorem lacinia consectetur.
        </p>

        <h3>Subsection</h3>

        <p>
          Donec ut librero sed accu vehicula ultricies a non tortor. Lorem ipsum
          dolor sit amet, consectetur adipisicing elit. Aenean ut gravida lorem.
          Ut turpis felis, pulvinar a semper sed, adipiscing id dolor.
        </p>

        <p>
          Pelientesque auctor nisi id magna consequat sagittis. Curabitur
          dapibus, enim sit amet elit pharetra tincidunt feugiat nist imperdiet.
          Ut convallis libero in urna ultrices accumsan. Donec sed odio eros.
        </p>

        <h3>Another subsection</h3>

        <p>
          Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus. Cum
          soclis natoque penatibus et manis dis parturient montes, nascetur
          ridiculus mus. In rutrum accumsan ultricies. Mauris vitae nisi at sem
          facilisis semper ac in est.
        </p>

        <p>
          Vivamus fermentum semper porta. Nunc diam velit, adipscing ut
          tristique vitae sagittis vel odio. Maecenas convallis ullamcorper
          ultricied. Curabitur ornare, ligula semper consectetur sagittis, nisi
          diam iaculis velit, is fringille sem nunc vet mi.
        </p>
      </article>

      <!-- the aside content can also be nested within the main content -->
      <aside>
        <h2>Related</h2>

        <ul>
          <li><a href="#">Oh I do like to be beside the seaside</a></li>
          <li><a href="#">Oh I do like to be beside the sea</a></li>
          <li><a href="#">Although in the North of England</a></li>
          <li><a href="#">It never stops raining</a></li>
          <li><a href="#">Oh well…</a></li>
        </ul>
      </aside>
    </main>

    <!-- And here is our main footer that is used across all the pages of our website -->

    <footer>
      <p>©Copyright 2050 by nobody. All rights reversed.</p>
    </footer>
  </body>
</html>

## How does metadata influence Search Engine Optimization?

metadata allows search engines to search specifically for topic words that can be associated with the website. This allows for ease of search with keywords.

## How is the <meta> HTML tag used when specifying metadata?

Metadata: the <meta> element
Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the <meta> element. Of course, the other stuff we are talking about in this article could also be thought of as metadata too. There are a lot of different types of <meta> elements that can be included in your page's <head>, but we won't try to explain them all at this stage, as it would just get too confusing. Instead, we'll explain a few things that you might commonly see, just to give you an idea.



[Back Home](../reading-notes/README.md)