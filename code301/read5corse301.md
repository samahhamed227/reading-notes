# React Docs - thinking in React
## How would you break a mock into a component heirarchy?

The MockServerRule starts MockServer (for both mocking and proxying) on a free port before the any test runs and stops MockServer after all tests have completed …

## What is the single responsibility principle and how does it apply to components?
It's a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part. All of that module, class or function's services should be narrowly aligned with that responsibility.

## What does it mean to build a ‘static’ version of your application?
It's means build components that reuse other components and pass data using props. props are a way of passing data from parent to child, and will not be using the state at all while building the static application.

## Once you have a static application, what do you need to add?

You’ll have a library of reusable components that render your data model. The components will only have render() methods since this is a static version of your app.
## What are the three questions you can ask to determine if something is state?
Is it passed in from a parent via props? If so, it probably isn’t state.

Does it remain unchanged over time? If so, it probably isn’t state.

Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?
we can know that if the object have to change some of what he have . vote .number. chape aof it .

