# Read 28 : Component Lifecycle / useEffect()

## Why do we not need more .html pages in a multi-page React app?

React apps are single page app ,A React app consists of a single HTML file index.html. The views are coded in JSX format as components.

## If we wanted a component to show up on every page, where would we put it and why?

- Outside the < BrowserRouter />
- **Inside the < BrowserRouter />, outside a < Route />**
- Inside a < Route />

Inside the < BrowserRouter/ >, outside a < Route/ >, to have it always no matter what the current route is .

## What does routing do with the components that were rendered when a new route is requested

It goes to the new componetnt and remove the old one cleans up

## What does props.children contain?

Children is a special property of React components which contains any child elements defined within the component, e.g. the divs inside Example above. {this.props.children} includes those children in the rendered result.

## How do useState() and this.setState() differ?

- The setState function is used to handle the state object in a React class component.

- SetState is merging the previous state with the new one, it means that you dont have to pass the full state object every time you want to change some part of the state. React will update given properties and won't touch the rest. The useState's updater rewrites a previous state with a new one and it does not perform any merging. Its just replacement instead of merging.

## Terms

| Term                            | Def                   |
| :-------------                  |   :----------         |
| State Hook                 |A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.|
|Mounting and Un-Mounting              |The main job of React is to figure out how to modify the DOM to match what the components want to be rendered on the screen.React does so by "mounting" (adding nodes to the DOM), "unmounting" (removing them from the DOM), and "updating" (making changes to nodes already in the DOM).|