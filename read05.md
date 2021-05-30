# images
## Adding Images


To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
alt
This provides a text description
of the image which describes the
image if you cannot see it.
title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.
# color
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
 hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread
# text
font-face allows you to use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.
Because this technique allows
a version of the font to be
downloaded to the user's
computer, it is important that the
license for the font permits it to
be used in this way.
You add the font to your style
sheet using the @font-face
rule, as shown on the right.
font-family
This specifies the name of the
font. This name can then be used
as a value of the font-family
property in the rest of the style
sheet (as shown in the rule for
the <h1> and <h2> elements).
src
This specifies the path to the
font. In order for this technique
to work in all browsers, you will
probably need to specify paths
to a few different versions of the
font, as shown on the next page.
format
This specifies the format that the
font is supplied in. (It's discussed
in detail on the next page.)