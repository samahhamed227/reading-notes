
# Links

![links](https://cdn.educba.com/academy/wp-content/uploads/2019/10/HTML-Text-Link.png.webp)
## Linking to Other Sites In HTML.

Links are created using the ``<a>
element which has an attribute 
called href. The value of the 
href attribute is the page that 
you want people to go to when 
they click on the link.
Users can click on anything that 
appears between the opening 
<a> ``tag and the closing </a>
tag and will be taken to the page 
specified in the href attribute 

 
For example <a href="http://www.empireonline.com">
 Empire</a> 
 `<a href="http://www.empireonline.com">
 Empire</a>`.

![link](https://www.copahost.com/blog/wp-content/uploads/2019/07/html-link.jpg)

 ## Linking to Other Pages on the Same Site

When you are linking to other 
pages within the same site, 
you do not need to specify the 
domain name in the URL. You 
can use a shorthand known as a 
relative URL.
If all the pages of the site are in 
the same folder, then the value 
of the href attribute is just the 
name of the file.

For Exmaple:-  
<a href="index.html">Home</a>  `<a href="index.html">Home</a> `   
 <a href="about-us.html">About</a> `<a href="about-us.html">About</a>`

![link](https://i.ytimg.com/vi/_6t8B2pu5k0/maxresdefault.jpg)
 ## Email Links

 To create a link that starts up 
the user's email program and 
addresses an email to a specified 
email address, you use the <a*>
element. However, this time the 
value of the href attribute starts 
with mailto: and is followed by 
the email address you want the 
email to be sent to.

For example:   
<a href="mailto:jon@example.org">Email Jon</a> `<a href="mailto:jon@example.org">Email Jon</a>`

## Opening Links in a New Window

If you want a link to open in a 
new window, you can use the 
target attribute on the opening 
<a*> tag. The value of this 
attribute should be _blank.

For exmaple:-
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> `<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a>` (opens in new window)

## Linking to a Specific Part of the Same Page
At the top of a long page 
you might want to add a list 
of contents that links to the 
corresponding sections lower 
down. Or you might want to add 
a link from part way down the 
page back to the top of it to save 
users from having to scroll back 
to the top.

For Exmaple:-  
<a href="#arc_shot">Arc Shot</a> `<a href="#arc_shot">Arc Shot</a>`    
<a href="#interlude">Interlude</a> `<a href="#interlude">Interlude</a>`

## Linking to a Specific Part of Another Page

If you want to link to a specific 
part of a different page (whether 
on your own site or a different 
website) you can use a similar 
technique.
As long as the page you are 
linking to has id attributes that 
identify specific parts of the 
page, you can simply add the 
same syntax to the end of the 
link for that page.
Therefore, the href attribute 
will contain the address for the 
page (either an absolute URL or 
a relative URL), followed by the 
#symbol, followed by the value 
of the id attribute that is used on 
the element you are linking to.
For example, to link to the 
bottom of the homepage of the 
website that accompanies this 
book, you would write:  

`<a href="http:/www.
htmlandcssbookcom/
#bottom"></a> `


# Layout

## Layout has 3 main topics 
1. Controlling the position of elements
2. Creating site layouts
3. Designing for different sized screens

### Key Concepts in Positioning Elements

Block-level boxes start on a new line and act as the main building blocks 
of any layout, while inline boxes flow between surrounding text. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors. 

### Block-level elements
start on a new line  
Examples include:
`<h1> <p> <ul> <li>`


### Inline elements
flow in between  surrounding text   
Examples include:  
`<img> <b> <i>`

## Containing Elements
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.
It is common to group a number of elements together inside a <div>
(or other block-level) element. For example, you might group together 
all of the elements that form the header of a site (such as the logo and 
the main navigation). The <div> element that contains this group of 
elements is then referred to as the containing element.

## Controlling the Position of Elements

1. Normal flow
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).

2. Relative Positioning
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.


3. Absolute positioningThis positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

4. Fixed Positioning 
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

5. Floating Elements
Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.

# Functions in Javescript

## WHAT IS A FUNCTION? 

Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

## Defining functions
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.  
A list of parameters to the function, enclosed in parentheses and separated by commas.   
The JavaScript statements that define the function, enclosed in curly brackets, {...}.  
For example, the following code defines a simple function named square:

`function square(number)   
 {  

  return number * number;
}`


## Calling functions

Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.  

Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function square, you could call it as follows:   

square(5);


## FUNCTION DECLARATION 
A function declaration creates a function that you 
can call later in your code. It is the type of function 
you have seen so far in this book. 
In order to call the function later in your code, you 
must give it a name, so these are known as named 
functions. Below, a function called area() is 
declared, which can then be called using its name. 

`function area (width, height)   

return width * height; 

}; 
var size= area (3, 4) ;`

## FUNCTION EXPRESSION 
If you put a function where the interpreter would 
expect to see an expression, then it is treated as an 
expression, and it is known as a function expression. 
In function expressions, the name is usually omitted. 
A function with no name is called an anonymous 
function. Below, the function is stored in a variable 
called area. It can be called like any function created 
with a function declaration. 

`var area = function(width, height) {     
r eturn width * height;       
} ;    
var size = area (3, 4) ;`

## VARIABLE SCOPE
 The location where you declare a variable will affect where it can be used 
within your code. If you declare it within a function, it can only be used 
within that function. This is known as the variable's scope.

## LOCAL VARIABLES 
When a variable is created inside a function using the 
var keyword, it can only be used in that function. 
It is called a local variable or function-level variable. 
It is said to have local scope or function-level scope. 
It cannot be accessed outside of the function in 
which it was declared. Below, area is a local variable. 
The interpreter creates local variables when the 
function is run, and removes them as soon as the 
function has finished its task. This means that: 
• If the function runs twice, the variable can have 
different values each time. 
• Two different functions can use variables with the 
same name without any kind of naming conflict.

## GLOBAL VARIABLES
If you create a variable outside of a function, then it 
can be used anywhere within the script. It is called a 
global variable and has global scope. In the example 
shown, wa 11 Size is a global variable. 
Global variables are stored in memory for as long 
as the web page is loaded into the web browser. 
This means they take up more memory than local 
variables, and it also increases the risk of naming 
conflicts (see next page). For these reasons, you 
should use local variables wherever possible. 
If you forget to declare a variable using the var 
keyword, the variable will work, but it will be treated 
as a global variable (this is considered bad practice).


function getArea(width, height) 
var area = width * height;     (one)
return area; 
var wallSize = getArea(3, 2);  (two)
document. write(wa 11 Size); 
(one) Is LOCAL (OR FUNCTION-LEVEL) SCOPE 
(two) Is GLOBAL SCOPE

# 6 Reasons for Pair Programming
Iterative loops. Code reviews. Fast feedback. Error checking and linting. These are software engineering practices that have proven to dramatically improve the quality of code developers produce. 
pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. 
![link](https://kcrecruitment.com/wp-content/uploads/2019/02/Programmers-img-min.jpg)

### How does pair programming work?
While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator.The Driver is the programmer who is typing and the only one whose hands are on the keyboard.


### Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

During a five-hour paired lab session, Code Fellows students work on all four of these language-specific skills. The abilities they foster will serve them well in completing assignments, in their own communication and learning, in interviews, and in readiness for a job at a company that utilizes this agile practice.

Wow, all that? Let’s take a look!

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness
