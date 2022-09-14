# Learning Markdown

## Headings

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

Heading level 1
===============

Heading level 2
---------------

> Ensure that there is a space between the Hashtag and the heading title

## Paragraphs 

Paragraphs are simply written in one or more lines of text. There is no need to indent.

## Line Breaks

Similarly line breaks simply require a line with two or more spaces. Type return or enter to do this.

Like this. :bowtie:

## Emphasis

### Bold

I just love **bold text**.

I just love __bold text__.

Love**is**bold

This is best practices Love**is**bold

### Italic

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

This is best practices A*cat*meow

### Bold & Italic

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.	

This is really***very***important text.

This technique is best practices This is really***very***important text.

## Blockquotes

> Rogelia followed her through many of the beautiful rooms in her castle.

> Rogelia followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep 

> Rogelia followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

This is best practice

Try to put a blank line before...

> This is a blockquote

...and after a blockquote.

## Lists

### Ordered Lists
1. First item
2. Second item
3. Third item
4. Fourth item

1. First item
1. Second item
1. Third item
1. Fourth item

1. First item
8. Second item
3. Third item
5. Fourth item

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

This is best practice

1. First item
2. Second item

### Unordered Lists
- First item
- Second item
- Third item
- Fourth item

* First item
* Second item
* Third item
* Fourth item

+ First item
+ Second item
+ Third item
+ Fourth item

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

#### Starting Unordered List Items with Numbers

- 1968\. A great year!
- I think 1969 was second best.

This is best practice
- First item
- Second item
- Third item
- Fourth item

## Code Blocks
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

## Images
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.

## Code
To denote a word or phrase as code, enclose it in backticks (').
At the command prompt, type `nano`.
### Escaping Backticks
``Use `code` in your Markdown file.``

## Horizontal Rules
Use three or more astericks, dashes, or underscores.
***
---
___________

This is best practice
Try to put a blank line before...

---

...and after a horizontal rule.

## Links
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
My second favorite search engine is [Google](https://google.com).

## Adding Titles
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URLs and Email Addresses
To quickly turn a URL or email address into a link, use angle brackets
<https://www.markdownguide.org>
<fake@example.com>

## Formatting Links
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

This is best practice
[link](https://www.example.com/my%20great%20page)

<a href="https://www.example.com/my great page">link</a>

## Images
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")

## Linking Images
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

## Escaping Characters
\* Without the backslash, this would be a bullet in an unordered list.

### Characters You Can Escape
\  | backslash
'  | backtick
*  | asterisk
_  | underscore
{} | curly braces
[] | brackets
<> | angle brackets
() | parentheses
#  | pound sign
+  | plus sign
-  | minus sign (hyphen)
.  | dot
!  | exclamation mark
|. | pipe

## HTML
Hypertext Markup Language
This **word** is bold. This <em>word</em> is italic.

# Part 2

## Headings

# The largest heading
## The second largest heading
###### The smallest heading

## Styling Text
Style	Syntax	Keyboard shortcut	Example	Output
Bold	                  ** ** or __ __	  Command+B (Mac) or Ctrl+B (Windows/Linux)	**This is bold text**	This is bold text
Italic	                * * or _ _      	Command+I (Mac) or Ctrl+I (Windows/Linux)	*This text is italicized*	This text is italicized
Strikethrough	          ~~ ~~		        ~~This was mistaken text~~	                This was mistaken text
Bold and nested italic	** ** and _ _		**This text is _extremely_ important**	    This text is extremely important
All bold and italic	    *** ***		       ***All this text is important***	          All this text is important
Subscript             	<sub> </sub>		<sub>This is a subscript text</sub>	        This is a subscript text
Superscript           	<sup> </sup>		<sup>This is a superscript text</sup>	      This is a superscript text

## Quoting Text
> Text that is a quote

## Quoting Code
Use `git status` to list all new or modified files that haven't yet been committed.

Some basic Git commands are:
```
git status
git add
git commit
```
## Supported Color Models
The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.

Color	 Syntax	         Example           	Output
HEX	   `#RRGGBB`	    `#0969DA`	          Rendered supported color model in HEX format.
RGB	   `rgb(R,G,B)`	 `rgb(9, 105, 218)`	  Rendered supported color model in RGB format.
HSL	   `hsl(H,S,L)`	 `hsl(212, 92%, 45%)`	Rendered supported color model in HSL format.

## Links

This site was built using [GitHub Pages](https://pages.github.com/).

## Images
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

Here are some examples for using relative links to display an image.

Context	                                                       Relative Link
In a .md file on the same branch	                             /assets/images/electrocat.png
In a .md file on another branch                       	      /../main/assets/images/electrocat.png
In issues, pull requests and comments of the repository	      ../blob/main/assets/images/electrocat.png?raw=true
In a .md file in another repository                         	/../../../../github/docs/blob/main/assets/images/electrocat.png
In issues, pull requests and comments of another repository	  ../../../github/docs/blob/main/assets/images/electrocat.png?raw=true

## Specifying the theme an image is shown to
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## Lists
- George Washington
- John Adams
- Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

1. First list item
   - First nested list item
     - Second nested list item

100. First list item
     - First nested list item

100. First list item
     - First nested list item
       - Second nested list item
       - 
### Task Lists
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

If a task list description begins with a parenthesis, you'll need to escape it with \
- [ ] \(Optional) Open a followup issue

## Mentioning people and teams
@github/support What do you think about these updates?

## Using Emoji
You can add emoji to your writing by typing :EMOJICODE:.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

## Footnotes
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
    
## Hiding content with comments
<!-- This content will not appear in the rendered Markdown -->

## Ignoring Markdown formatting
Let's rename \*our-new-project\* to \*our-old-project\*.


This site was built using [GitHub Pages](https://pages.github.com/)

Contact Info:
David Sitthideth
Email: Trajan996@yahoo.com









