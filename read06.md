


# What is the hardest thing about writing code?

There are many common answers to this question:

1.Learning a new technology
2.Naming things
3.Testing your code
4.Debugging
5.Fixing bugs
6.Making software maintainable


# Why problem domains are hard
1.Figure out what the major components of the picture are
2.Sort the pieces by color or component
3.3Put together all the border pieces
4.Put together each component of the picture from the piles you created

# What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

1.Make the problem domain easier
2.Get better at understanding the problem domain


# WHAT IS AN OBJECT? 
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names.

- If a variable is part of an object, it is called a 
property
- If a function is part of an object, it is called a method. 
- Like variables and named functions,  properties and methods have a 
name and a value. In an object, that name is called a key. 
- An object cannot have two keys with the same name. 
- The value of a property can be a string, number, Boolean, array, or 
even another object.
- This object is called hotel which represents a hotel called Quay 
with 40 rooms (25 of which have 
been booked). 

### The only things changing in the 
code are the values of the hot e 1 
object's properties: 
• The name of the hotel 
• How many rooms it has 
• How many rooms are booked

## The Document Object Model (DOM) specifies 

![dom](https://www.researchgate.net/profile/Jian-Chang-8/publication/254002847/figure/fig1/AS:298235726974978@1448116346303/Example-of-DOM-Node-Tree.png)

# What is the DOM?
The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page

how browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window.

# Interfaces and Objects
Many objects borrow from several different interfaces. The table object, for example, implements a specialized HTMLTableElement interface, which includes such methods as createCaption and insertRow. But since it's also an HTML element, table implements the Element interface described in the DOM Element Reference chapter. And finally, since an HTML element is also, as far as the DOM is concerned, a node in the tree of nodes that make up the object model for an HTML or XML page, the table object also implements the more basic Node interface, from which Element derives.


# API = DOM + JavaScript

### In the beginning, JavaScript and the DOM were tightly intertwined, but eventually, they evolved into separate entities. The page content is stored in the DOM and may be accessed and manipulated via JavaScript, so that we may write this approximative equation:

# TRAVERSING THE DOM 
1. parentNode 
2. previousSibling nextSibling 
3. firstChil d 
lastChild 


# WHITESPACE NODES 
Traversing the DOM can be difficult because 
some browsers add a text node whenever they 
come across whitespace between elements. 

![api](https://th.bing.com/th/id/Rc777ca9ba492337931700c44de5d2a44?rik=RbZmwFFopgXXTA&pid=ImgRaw)
# HOW TO GET/UPDATE  ELEMENT CONTENT
Take a look at the three examples of <1 i> elements 
on the right. Each one adds some more markup and, 
as a result, the fragment of the DOM tree for each 
list item is very different. 
• The first (on this page) just contains text. 
• The second and third (on the right-hand page) 
contain a mix of text and an <em> element. 
• Navigate to the text nodes
• Work with the containing element. 
• The <em> element node has its own child text 
node which contains the word fresh. 
• The original text node is now a sibling of the node 
that represents the <em> element.
 The first child of the <l i >element is a text node, 
which contains the word six. 
• It has a sibling which is an element node for the 
<em> element. In turn, that <em> element node 
has a child text node containing the word fresh. 
• Finally, there is a text node holding the word 
figs, which is a sibling of both the text node for 
the word "six" and the element node, <em>.

# ADDING ELEMENTS USING 
DOM MANIPULATION 
DOM manipulation offers another technique 
to add new content to a page (rather than 
i nnerHTML). It involves three steps: 
1 CREATE THE ELEMENT 
createEl ement () 
2 GIVE IT CONTENT
createTextNode()
3 ADD IT TO THE DOM 
 appendChild() 


# EXAM INING THE DOM IN CHROME

 In the screenshot to the right, the 
<l i> element is highlighted and 
the Properties panel (1) indicates 
that this is an: 
• 1 i element with an id 
attribute whose value is one 
and cl ass whose value is hot 
• an HTMLLIElement 
• an HTMLElement 
• an element 
• a node 
• an object 
![img](https://developer-chrome-com.imgix.net/image/admin/Tynv55DnsSgtvpd6Iz9z.png?auto=format)