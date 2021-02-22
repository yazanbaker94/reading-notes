# Understanding CSS:
Thinking Inside the Box




* The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.


* CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented.

* <link> chapter-10/using-external-css.html HTML
The <link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.


* href
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).

*  type
This attribute specifies the type
of document being linked to. The
value should be text/css.

*  rel
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file 



* <style>
You can also include CSS rules
within an HTML page by placing
them inside a <style> element,
which usually sits inside the
<head> element of the page. 

*  There are many different types
of CSS selector that allow you to
target rules to specific elements
in an HTML document

1. Universal Selector
2. Type Selector
3. Class Selector
4. ID Selector
5. Child Selector
6. Descendant Selector
7. Adjacent Sibling
Selector
8. General Sibling
Selector



### LAST RULE
If the two selectors are identical,
the latter of the two will take
precedence. Here you can see
the second i selector takes 


### SPECIFICITY
If one selector is more specific
than the others, the more
specific rule will take precedence
over more general ones. In this
example:
h1 is more specific than *
p b is more specific than p
p#intro is more specific than p



### You can force a lot of properties
to inherit values from their
parent elements by using
inherit for the value of the
properties. In this example, the
<div> element with a class
called page inherits the padding
size from the CSS rule that
applies to the <body> element.


* All of your web pages can share
the same style sheet. This is
achieved by using the <link>
element on each HTML page of
your site to link to the same CSS
document. This means that the
same code does not need to be
repeated in every page (which
results in less code and smaller
HTML pages). 

### CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
* Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
* Different types of selectors allow you to target your
rules at different elements.
* Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document,
although they may appear within an HTML page



* rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

* hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80


* color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan

* This example shows a pH scale to demonstrate
the different ways that colors can be specified
using CSS (using color names, hex codes, RGB,
and HSL).

* Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
