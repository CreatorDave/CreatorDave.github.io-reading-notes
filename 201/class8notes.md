
## Flexbox is designed for one-dimensional content. Explain what this means.

It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

When a flex container wraps it creates multiple flex lines. In terms of space distribution, each line acts like a new flex container. Therefore if you are wrapping rows, it is not possible to get something in row 2 to line up with something above it in row 1.

## Explain the difference between the main axis and cross axis
The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.

The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

## How can using certain properties of flexbox negatively impact accessibility?
using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

## What are some advantages of using flexbox over float?
* Vertically centering a block of content inside its parent.
* Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
* Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

## How does this topic connect with your long term goals?
Building out CSS layouts will make my websites more responsive.

[Back Home](../reading-notes/README.md)