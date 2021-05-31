# OBJECT LITERALS 
JAVASCRIPT
var hotel = {
name: 'Park',
rooms: 120,
booked : 77,
c03/js/ object-l iteral2.js
checkAvailabi lity: function() {
return this.rooms - this.booked;
}
} ;
var elName = document .getElementByid('hotelName') ;
elName .textContent =hotel .name ;
var el Rooms = document .getElementByid( 'rooms') ;
e 1 Rooms . text Content = hote 1 . checkAvai l abi lity();
l;IJiiJ51
Here you can see another object.
Again it is called hote 1, but this
time the model represents a
different hotel. For a moment,
imagine that this is a different
page of the same travel website.
The Park hotel is larger. It has
120 rooms and 77 of them are
booked.
The only things changing in the
code are the values of the hot e 1
object's properties:
• The name of the hotel
• How many rooms it has
• How many rooms are booked
The rest of the page works in
exactly the same way. The name
is shown using the same code.
The checkAvai 1 abi l ity()
method has not changed and is
called in the same way.
If this site had 1,000 hotels,
the only thing that would
need to change would be the
three properties of this object.
Because we created a model for
the hotel using data, the same
code can access and display the
details for any hotel that follows
the same data model.
If you had two objects on the
same page, you would create
each one using the same
notation but store them in
variables with different names. 

# Object Literal Syntax
Object literals are defined using the following syntax rules:

A colon separates property name[1] from value.
A comma separates each name-value pair from the next.
A comma after the last name-value pair is optional.[2]
If any of the syntax rules are broken, such as a missing comma or colon or curly brace, a JavaScript error will be triggered. Browser error messages are helpful in pointing out the general location of object literal syntax errors, but they will not necessarily be completely accurate in pointing out the nature of the error.

# Document Object Model
THE DOCUMENT NODE
Above, you can see the HTML code for a shopping
list, and on the right hand page is its DOM tree.
Every element, attribute, and piece of text in the
HTML is represented by its own DOM node.
At the top of the tree a document node is added; it
represents the entire page (and also corresponds to
the document object, which you first met on p36).
When you access any element, attribute, or text
node, you navigate to it via the document node. It is
the starting point for all visits to the DOM tree.
s DOCUMENT OBJECT MODEL
ELEMENT NODES
HTML elements describe the structure of an HTML
page. (The <h l > - <h6> elements describe what
parts are headings; the <p> tags indicate where
paragraphs of text start and finish; and so on.)
To access the DOM tree, you start by looking for
elements. Once you find the element you want, then
you can access its text and attribute nodes if you
want to. This is why you start by learning methods
that allow you to access element nodes, before
learning to access and alter text or attributes. 