What is a real world use case for the alt attribute being used in a website?
A photo on a website. The photo needs the alt attribute to indicate what kind or the name of the photo.

How can you improve accessibility of images in an HTML document?
Using alternative text for the visually impaired allows a screen reader to read the image out loud to the user.

Provide an example of when the figure element would be useful in an HTML document.
<figure> or <figcaption> purpose is to provide a semantic container for figures, and to clearly link the figure to the caption. So again aiding the visually impaired with identifying what photo goes with which caption.

Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
gif is a good choice for simple images and animations.
svg ideal for user interface elements, icons, diagrams where accuracy matters.

What image type would you use to display a screenshot on your website and why?
Lossless WebP or PNG;
JPEG if compression artifacts aren't a concern
It prevents lossy compression. Things look sharp.

Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

background-color
The background color to use in areas of the element that have no foreground content.

 the color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color.

 Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

The background-color is set using the HSL value specified using hsl(270deg, 50%, 75%). This is a medium purple color.
The box's outline is used to specify that the box should be enclosed in a four pixel thick dashed line whose color is a somewhat deeper purple (rgb(110, 20, 120)).
The foreground (text) color is specified by setting the color property to hsl(0deg, 100%, 100%). This is one of many ways to specify the color white.
We add a green wavy line under the text with text-decoration.
Finally, a bit of a shadow is added to the text using text-shadow. Its color parameter is set to black.

What should you consider when choosing fonts for an HTML document?
Font styles: Properties that affect a text's font, e.g., which font gets applied, its size, and whether it's bold, italic, etc.
Text layout styles: Properties that affect the spacing and other layout features of the text, allowing manipulation of, for example, the space between lines and letters, and how the text is aligned within the content box.
Color, Font families default fonts, font-stacks, font-size, font style, font weight, text transform, and text decoration are more things to consider. Text drop shadows, text layout, text alignment, line height, letter and word spacing, and font shorthand.

What do font-size, font-weight, and font-style do to HTML text elements?
Adjusts the font size which starts at 16px. 
font-weight: Sets how bold the text is. This has many values available in case you have many font variants available (such as -light, -normal, -bold, -extrabold, -black, etc.), but realistically you'll rarely use any of them except for normal and bold:
normal, bold: Normal and bold font weight.
lighter, bolder: Sets the current element's boldness to be one step lighter or heavier than its parent element's boldness.
100 – 900: Numeric boldness values that provide finer grained control than the above keywords, if needed.

font-style: Used to turn italic text on or off. Possible values are as follows (you'll rarely use this, unless you want to turn some italic styling off for some reason):
normal: Sets the text to the normal font (turns existing italics off).
italic: Sets the text to use the italic version of the font, if available; if not, it will simulate italics with oblique instead.
oblique: Sets the text to use a simulated version of an italic font, created by slanting the normal version.


Describe two ways you could add spacing around the characters displayed in an h1 element.
The letter-spacing and word-spacing properties allow you to set the spacing between letters and words in your text. You won't use these very often, but might find a use for them to obtain a specific look, or to improve the legibility of a particularly dense font. They can take most length and size units.

[Back Home](../reading-notes/README.md)