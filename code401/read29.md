# Advanced State with Reducers

1. How can we ensure that an effect hook runs only once?
> If we provide an empty array on the second argument of the useEffect.

2. Can useState() update more than one state variable at the same time?
> You could combine the state into one state object and then you could do one setState call and there will only be one render. Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.

## Is useState() synchronous?

useState and setState both are asynchronous. Even though they are asynchronous, the useState and setState functions do not return promises. Therefore we cannot attach a then handler to it or use async/await to get the updated state values.

## Terms

| Term                            | Def                   |
| :-------------                  |   :----------         |
| State Hook                 |A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.|
|Component Lifecycle              |Component Lifecycle the series of methods that are invoked in different stages of the component’s existence. The three phases are: Mounting, Updating, and Unmounting.|