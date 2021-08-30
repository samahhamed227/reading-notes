
## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
‘render’

## What is the very first thing to happen in the lifecycle of React?
Mounting

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1. constructor
2. render
3. React Updates
4. componentDidMount
5. componentWillUnmount


## What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. 


# Rebuilt with React
React-Bootstrap replaces the Bootstrap JavaScript. Each component has been built from scratch as a true React component, without unneeded dependencies like jQuery.

# Bootstrap at its core
Built with compatibility in mind, we embrace our bootstrap core and strive to be compatible with the world's largest UI ecosystem.

# Accessible by default
The React component model gives us more control over form and function of each component.



## Give your sites the edge
Create amazing experiences for the web in record time—without thinking once about servers or devops.
1. Connect your repository
Netlify detects the changes to push to git and triggers automated deploys.

2. Add your build settings
Netlify provides you a powerful and totally customizable build environment.

3. Deploy your website
Publishing is seamless with instant cache invalidation and atomic deploys.


# What types of things can you pass in the props?
Be sure to pass props as an argument to the entire functional component first. When referencing a prop, it must be in curly braces.

If we are passing the prop to a class component, it will look slightly different.

#  What is the big difference between props and state?
The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.
State can be changed (Mutable)
Whereas Props can't (Immutable)


# When do we re-render our application?
React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically.

# What are some examples of things that we could store in state?
 

You store the state of your app in redux. How you structure your state tree is up to you. You can think of the state tree as one giant javascript object. With redux, you would ideally store as little component state in your react components themselves and instead move that to the redux state tree.

For example, if you fetched some user data, you could store that in the redux state such that your connected components have access to that data now. You can also get more granular and store states that describe certain UI components. A part of your state that describes a dropdown could look like this

{
  myDropdown: {
    isOpen: false,
    options: [
      'apple',
      'orange'
    ]
  }
}
I believe a good point to start incorporating redux is when your app gets to a certain point where your components are no longer just "dumb" components that display data.

Edit: To try and answer the question "when should I connect my components?". I struggled with this myself but don't have a great answer yet. Right now I typically connect a component if I am passing down props through many ancestor components just for that component specifically. So connecting would avoid that boilerplate code altogether.



## Adding Lifecycle Methods to a Class
In applications with many components, it’s very important to free up resources taken by the components when they are destroyed.
##  State Updates May Be Asynchronous
React may batch multiple setState() calls into a single update for performance. 

## State Updates are Merged
When you call setState(), React merges the object you provide into the current state.

## The Data Flows Down
Neither parent nor child components can know if a certain component is stateful or stateless, and they shouldn’t care whether it is defined as a function or a class.

# Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

React events are named using camelCase, rather than lowercase.
With JSX you pass a function as the event handler, rather than a string.

# Passing Arguments to Event Handlers
Inside a loop, it is common to want to pass an extra parameter to an event handler.

## The tutorial is divided into several sections:

Setup for the Tutorial will give you a starting point to follow the tutorial.
Overview will teach you the fundamentals of React: components, props, and state.
Completing the Game will teach you the most common techniques in React development.
Adding Time Travel will give you a deeper insight into the unique strengths of React.



## What Are We Building?
In this tutorial, we’ll show how to build an interactive tic-tac-toe game with React.

You can see what we’ll be building here: Final Result. If the code doesn’t make sense to you, or if you are unfamiliar with the code’s syntax, don’t worry! The goal of this tutorial is to help you understand React and its syntax.

1. Setup Option 1: Write Code in the Browser
2. Setup Option 2: Local Development Environment

## Prerequisites
We’ll assume that you have some familiarity with HTML and JavaScript, but you should be able to follow along even if you’re coming from a different programming language. We’ll also assume that you’re familiar with programming concepts like functions, objects, arrays, and to a lesser extent, classes.

# Function Components
We’ll now change the Square to be a function component.

In React, function components are a simpler way to write components that only contain a render method and don’t have their own state. Instead of defining a class which extends React.Component, we can write a function that takes props as input and returns what should be rendered. Function components are less tedious to write than classes, and many components can be expressed this way.


# Showing the Past Moves
Since we are recording the tic-tac-toe game’s history, we can now display it to the player as a list of past moves.

We learned earlier that React elements are first-class JavaScript objects; we can pass them around in our applications. To render multiple items in React, we can use an array of React elements.