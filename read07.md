# Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain

# Model epic fails videos
Imagine you've been tasked to build a program that models the popularity of epic fail videos. 

# Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an EpicFailVideo object.
As you can see, the constructor function is defined using a function expression. 

# This is object-oriented programming in JavaScript at its most fundamental level.

The new keyword instantiates (i.e. creates) an object.
The constructor function initializes properties inside that object using the this variable.
The object is stored in a variable for later use.

# Generate random numbers
To model the random nature of user behavior, you'll need the help of a random number generator.
As you can see, methods can be added to a constructor function's prototype.
# Calculate daily Likes
Popularity of a video is measured in Likes. And the formula for calculating Likes is the number of viewers times the percentage of viewers who'll Like a video. In other words, viewers times percentage.

# Calculate weekly Likes
In addition to modeling the daily Likes, your boss has asked you to model the weekly Likes too. Little does your boss know how easy it is to add behaviors to your domain model.


- Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

- Here's some tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.
![image](https://homepages.fhv.at/thjo/lecturenotes/sysan/figures/domain/domain_umlclassdiagram.png)

# HTML Tables
HTML tables allow web developers to arrange data into rows and columns.

he <table. > tag defines an HTML table.

Each table row is defined with a <tr. > tag. Each table header is defined with a <th.> tag. Each table data/cell is defined with a <td.> tag.

By default, the text in <th.> elements are bold and centered.

By default, the text in <td.> elements are regular and left-aligned.
Note: The <td. > elements are the data containers of the table.
They can contain all sorts of HTML elements; text, images, lists, other tables, etc.
![image](https://d3i71xaburhd42.cloudfront.net/8ffcad9346c4978a211566fde6807d6fb4bfa5ed/13-Table7-1.png)
- To add a border to a table, use the CSS border property

- To let the borders collapse into one border, add the CSS border-collapse property

- Cell padding specifies the space between the cell content and its borders.

If you do not specify a padding, the table cells will be displayed without padding.

To set the padding, use the CSS padding property

- By default, table headings are bold and centered.

To left-align the table headings, use the CSS text-align property

- Border spacing specifies the space between the cells.

To set the border spacing for a table, use the CSS border-spacing property

- To make a cell span more than one column, use the colspan attribute

-To add a caption to a table, use the <caption> tag

 -To define a special style for one particular table, add an id attribute to the table
![img](https://upload.wikimedia.org/wikipedia/commons/f/ff/Tabel_rapport_reisuitgaven.png)

# Functions :
Since JS functions are JS objects, they can be stored in variables, passed as arguments to functions, returned by functions, have properties and can be changed dynamically. Therefore, functions are first-class citizens, and JavaScript can be viewed as a functional programming language,

- where theNameOfMyFunction is optional. When it is omitted, the function is anonymous. In any case, functions are invoked via a variable that references the function. In the above case, this means that the function is invoked with myFunction(), and not with theNameOfMyFunction().

Anonymous function expressions are called lambda expressions (or shorter lambdas) in other programming languages.
![im](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/02/Python-Functions-vs-Methods-01.jpg)


# Methods

### The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Read more about the this keyword at JS this Keyword.

## JavaScript Methods
JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.

## Accessing Object Methods
You access an object method with the following syntax:
![obj](https://miro.medium.com/max/1200/1*0ttFuc9a8RMCQxCbrNeMNg.png)
objectName.methodName()
You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

## Using Built-In Methods
This example uses the toUpperCase() method of the String object, to convert a text to uppercase:

let message = "Hello world!";
let x = message.toUpperCase();