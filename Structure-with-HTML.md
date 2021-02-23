
# Duckett: HTML & CSS, Chapter 18 - Process & Design

## Target Audience: individuals
* What is the age range of your target audience?
* Will your site appeal to more women or men? What is the mix?
* Which country do your visitors live in?
* Do they live in urban or rural areas?
* What is the average income of visitors?
* What level of education do they have?
* What is their marital or family status?
* What is their occupation?
* How many hours do they work per week?
* How often do they use the web?
* What kind of device do they use to access the web?




* Your content and design should
be influenced by the goals of
your users. 


1. The first attempts to discover
the underlying motivations for
why visitors come to the site.
2. The second examines the
specific goals of the visitors.
These are the triggers making
them come to the site now


## How Often People Will
Visit Your Site


*  Some sites benefit from being updated more
frequently than others. Some information (such
as news) may be constantly changing, while
other content remains relatively static.



#  Site Maps

* Now that you know what needs to appear
on your site, you can start to organize the
information into sections or pages


![example site map](https://i.ibb.co/HhymCZt/Capture.png)

##  WireFrames

* A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

## Example Wireframe

![example site map](https://i.ibb.co/BCVWP2M/Capture.png)



* Visual hierarchy refers to the order in which your eyes perceive what
they see. It is created by adding visual contrast between the items being
displayed. Items with higher contrast are recognized and processed first.


* Designing Navigation
 * Concise
 * Clear
 * Selective
 * Context
 * Interactive
 


#####  Summary
PROCESS & Design
* It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.
* Site maps allow you to plan the structure of a site.
* Wireframes allow you to organize the information that
will need to go on each page.
* Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.
* You can differentiate between pieces of information
using size, color, and style.
* You can use grouping and similarity to help simplify
the information you present.





* Tags act like containers. They tell you
something about the information that lies
between their opening and closing tags.


* Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.

*  Body, Head & Title

* HTML pages are text documents.
* HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
* Tags are often referred to as elements.
* Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
* Opening tags can carry attributes, which tell us more
about the content of that element.
* Attributes require a name and a value.
* To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.



* The <header> and <footer>
elements can be used for:
* The main header or footer
that appears at the top or
bottom of every page on the
site.
* A header or footer for an
individual <article> or
<section> within the page.




*  The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.




*  The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not.
When the <aside> element
is used inside an <article>
element, it should contain
information that is related to the
article but not essential to its
overall meaning. For example, a
pullquote or glossary might be
considered as an aside to the
article it relates to.



*  The <section> element groups
related content together, and
typically each section would
have its own heading.



* The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading. 


* You already met the <figure>
element in Chapter 5 when we
looked at images. It can be used
to contain any content that is
referenced from the main flow of
an article (not just images). 



* However, the <div> element
will remain an important way to
group together related elements,
because you should not be using
these new elements that you
have just met for purposes other
than those explicitly stated.

*  HTML5 allows web page authors
to place an <a> element around
a block level element that
contains child elements. This
allows you to turn an entire block
into a link.


*  Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.


*  <!-- -->
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:


*  Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).


*  Examples of block elements are
<h1>, <p>, <ul>, and <li>


*  Examples of inline elements are
<a>, <b>, <em>, and <img>.


* 
The <span> element acts like
an inline equivalent of the <div>
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements


*  An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame.

*  seamless
In HTML5, a new attribute
called seamless can be applied
to an iframe where scrollbars
are not desired. The seamless
attribute (like some other new
HTML5 attributes) does not
need a value, but you will often
see authors give it a value of
seamless. Older browsers
do not support the seamless
attribute.



*  <meta>
The <meta> element lives
inside the <head> element and
contains information about that
web page

1. description
2. keywords
3. robots


*  The <meta> element also
uses the http-equiv and
content attributes in pairs.
In our example, you can see
three instances of the httpequiv attribute. Each one has a
different purpose:


1. author
2. pragma
3. expires



* DOCTYPES tell browsers which version of HTML you
are using.
* You can add comments to your code between the
<!-- and --> markers.
* The id and class attributes allow you to identify
particular elements.
* The <div> and <span> elements allow you to group
block-level and inline elements together.
* <iframes> cut windows into your web pages through
which other pages can be displayed.
* The <meta> tag allows you to supply all kinds of
information about your web page.
* Escape characters are used to include special
characters in your pages such as <, >, and ©.

