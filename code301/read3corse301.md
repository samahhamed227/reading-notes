# React Docs - lists and keys

## What does .map() return?
Consider an array of objects that contains user id and name. To display it to the DOM, you need to use the map() function and return JSX from the callback function. This is the most common use case of the map() function in React.
It's returned the result to the variable it has been assigned to.


## If I want to loop through an array and display each value in JSX, how do I do that in React?

we can build collections of elements and include them in JSX using curly braces {}.And we loop through them by using the JavaScript map() function.Which will return an html element for each time, and we assign the resulting array of elements to the variable we have declare it.


## Each list item needs a unique ____.
key wich is a special string attribute you need to include when creating lists of elements.
Keys used within arrays should be unique among their siblings. However, they don’t need to be globally unique. We can use the same keys when we produce two different arrays

## What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed, and it should be given to the elements inside the array to give the elements a stable identity.

# The Spread Operator

## What is the spread operator?
InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

## List 4 things that the spread operator can do.
1. Copying an array
2. Using Math functions
3. Using an array as arguments
4. Adding to state in React


# Give an example of using the spread operator to combine two arrays.
const arr1 = [1,2,3]
const arr2 = [4,5,6]
const arr3 = [...arr1, ...arr2] //arr3 ==> [1,2,3,4,5,6]

# Give an example of using the spread operator to add a new item to an array.
let numberStore = [0, 1, 2];
let newNumber = 12;
numberStore = [...numberStore, newNumber];

# Give an example of using the spread operator to combine two objects into one.
let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);





# How to Pass Functions Between Components

## In the video, what is the first step that the developer does to pass functions between components?
He loop through the array that need to be modified by using the map method with the access to that array with this.state.people (the name of the array),Then he return the created object that will access to each object inside the array so it will be modified.


## In your own words, what does the increment function do?.
It will loop inside the objectof the main array and find a matching with the data that has been passed to the function, then it will increament the count inside the object that has been passed.Then it returned to the new variable that been declared, so after that it update the state of the object in the main array.

## How can you pass a method from a parent component into a child component?
In the child component at it's own function we pass it with this.props with the name of the function we've create it to change the state in the parent component as calling it with the data that we need to change.
As in the video this.props.increament(this.props.name);

and in the parent component we pass it as any other props by name and the value that refrence to the funtion we created to change the state of the objects.

As in the video increament={this.increament};

## How does the child component invoke a method that was passed to it from a parent component?
When the action that we need to been taken from the user is done,like in the vidoe click on the button, the method we called that we added to the child componant function which will be sended to the parent componant and make the state changed.