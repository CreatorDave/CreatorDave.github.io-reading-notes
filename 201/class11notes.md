## Explain how the ability to use video and audio on the web has evolved since the early 2000s.
The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

## Describe the use of the src and controls attributes in the <video> element.
The features of note are:

src
In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.

controls
Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

The paragraph inside the <video> tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

## Why is it important to have fallback content inside the <video> element?
The paragraph inside the <video> tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

## Write a very short story where <audio> and <video> are characters.
Audio tells video what it wants to say. One day video decides to add audio to his band. Now that audio is a band of the band you can hear and not just see what's going on.

## How does Grid layout differ from Flex?
grid – generates a block-level grid
inline-grid – generates an inline-level grid
Defines a grid template by referencing the names of the grid areas which are specified with the grid-area property. Repeating the name of a grid area causes the content to span those cells. A period signifies an empty cell. The syntax itself provides a visualization of the structure of the grid.

## Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.
Grid Item
The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

## Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
Ease across browsers

## Define the following <img> attributes srcset and sizes. Write an example of how they are used.
— srcset/sizes/<picture> — are all supported in modern desktop and mobile browsers (including Microsoft's Edge browser, although not Internet Explorer.)
We can however use two attributes — srcset and sizes — to provide several additional source images along with hints to help the browser pick the right one. You can see an example of this in our responsive.html example on GitHub (see also the source code):
<img
  srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"
  sizes="(max-width: 600px) 480px,
         800px"
  src="elva-fairy-800w.jpg"
  alt="Elva dressed as a fairy" />

## How is srcset more helpful for responsive images than CSS or JavaScript?
The srcset and sizes attributes look complicated, but they're not too hard to understand if you format them as shown above, with a different part of the attribute value on each line. Each value contains a comma-separated list, and each part of those lists is made up of three sub-parts. Let's run through the contents of each now:

srcset defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma. For each one, we write:

An image filename (elva-fairy-480w.jpg)
A space
The image's intrinsic width in pixels (480w) — note that this uses the w unit, not px as you might expect. An image's intrinsic size is its real size, which can be found by inspecting the image file on your computer (for example, on a Mac you can select the image in Finder and press Cmd + I to bring up the info screen).
sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true — these are the hints we talked about earlier. In this case, before each comma we write:

A media condition ((max-width:600px)) — you'll learn more about these in the CSS topic, but for now let's just say that a media condition describes a possible state that the screen can be in. In this case, we are saying "when the viewport width is 600 pixels or less".
A space
The width of the slot the image will fill when the media condition is true (480px)

[Back Home](../reading-notes/README.md)