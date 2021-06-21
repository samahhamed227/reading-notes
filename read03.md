# Lists
Lists are used to group together related pieces of information so they are clearly associated with each other and easy to read. In modern web development, lists are workhorse elements, frequently used for navigation as well as general content.

## Type 
-There are three types of HTML lists: ordered (ol/li), 
unordered(ul/li), and definition(dd/dt/dl). 
- Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology.
- Lists can be nested inside one another

# Boxes 
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

## Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent


-CSS treats each HTML element as if it has its own box. 
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding 
for each box with CSS.
- It is possible to hide elements using the display and 
visibility properties.
- Block-level boxes can be made into inline boxes, and 
inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of 
boxes containing text and the leading.
- CSS3 has introduced the ability to create image 
borders and rounded borders


## Array

 ``Objects allow you to store keyed collections of values. That’s fine.
 ![array](https://miro.medium.com/max/2560/1*ffn_8KUwJzhcDuQP5a4oow.jpeg)

But quite often we find that we need an ordered collection, where we have a 1st, a 2nd, a 3rd element and so on. For example, we need that to store a list of something: users, goods, HTML elements etc.
![array1](https://foxbits.dev/sites/default/files/inline-images/array-slice-example-fruits-for-fact-0.jpg)

It is not convenient to use an object here, because it provides no methods to manage the order of elements. We can’t insert a new property “between” the existing ones. Objects are just not meant for such use.

There exists a special data structure named Array, to store ordered collections.``

## Declaration
### There are two syntaxes for creating an empty array:

1. let arr = new Array();
2. let arr = [];



## JavaScript switch
### The switch is a conditional statement like if statement. Switch is useful when you want to execute one of the multiple code blocks based on the return value of a specified expression.
![switch](https://koicha.dev/img/switch_case.jpg)
```Syntax:   
switch(expression or literal value){            
    case 1:   
        //code to be executed   
      break;  
    case 2:
        //code to be executed  
        break;   
    case n:  
        //code to be executed   
        break;   
    default:   
        //default code to be executed    
        //if none of the above case executed
}
```


 ### As per the above syntax, switch statement contains an expression or literal value. An expression will return a value when evaluated. The switch can includes multiple cases where each case represents a particular value. Code under particular case will be executed when case value is equal to the return value of switch expression. If none of the cases match with switch expression value then the default case will be executed.
