## When you want to use JavaScript with a web page, you use the HTML
<script> element to tell the browser it is coming across a script.
Its s re attribute tells people where the JavaScript file is stored. 


## You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files).

## When the browser comes across a <script> element, it stops to
load the script and then checks to see if it needs to do anything. 


## It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.
The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).
If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.


## A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 


## You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code. 

## A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables. 

## A variable is a good name for this
concept because the data stored
in a variable can change (or vary)
each time a script runs. 



## JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans. 



* NUMERIC DATA TYPE 

* STRING DATA TYPE 

* BOOLEAN DATA TYPE 


##  You can also use a technique
called escaping the quotation
characters. This is done by
using a backwards slash (or
"backslash") before any type of
quote mark that appears within
a string (as shown on the fourth
line of this code sample).
The backwards slash tells the
interpreter that the following
character is part of the string,
rather than the end of it. 


## A Boolean variable can only have
a value of true or fa 1 se, but this
data type is very helpful. 


## Programmers sometimes use
shorthand to create variables.
Here are three variations of how
to declare variables and assign
them values


## Once you have assigned a value
to a variable, you can then
change what is stored in the
variable later in the same script.

## Here are six rules you must always follow when giving a variable a name: 


* The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number


* The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name. 

*  You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.
ONLINE EXTRA
View a full list of keywords and
reserved words in JavaScript

*  All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases. 

* Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age. 

* If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash).
