# Context API

Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
**Using context, we can avoid passing props through intermediate elements**

![c](https://i.ytimg.com/vi/6uBgda52yEo/maxresdefault.jpg)

## Describe use cases useState() vs useReducer()

- useState is a Basic Hook for managing simple state transformation and useReducer is an Additional Hook for managing more complex state logic, it is worth noting that useState uses the useReducer internally. This implies that you could use useReducer for everything you can do with useState.

- useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

## Why do custom hooks need the use prefix?

Custom hooks are normal JS functions, named with the prefix ‘use’, that can use hooks inside of it and contain a common stateful logic to be reused in other components.

## What do custom hooks usually do?

## Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks

- Using any list of custom hooks, research and name one that you think will be useful in your applications
useClippy A hook for copying data to the clipboard and retrieving/pasting it using Ctrl-C/Command-C and Ctrl-V/Command-V.

- useBrowserContextCommunication useBrowserContextCommunication uses the Broadcast Channel API to deliver an easy solution for communication between different browser contexts (tabs, iframes, windows).

- useScript useScript is a hook for loading (and notifying when they’re loaded) external scripts, dynamically.

## Describe how a hook that fetches API data might work

The most accessible way to fetch data with React is using the Fetch API.

To make a simple GET request with fetch we just need to include the URL endpoint to which we want to make our request. We want to make this request once our React component has mounted.

we make our request within the useEffect hook, and we make sure to provide an empty dependencies array as the second argument, so that our request is only made once.

The useEffect hook gets invoked as soon as the component is mounted. If we need the hook to rerun based on some prop or state changes, we’ll need to pass them to the dependency array (which is the second argument of the useEffect hook)

## Document the following Vocabulary Terms

**useReducer**
 is one of the additional Hooks , An alternative to the useState Hook, it helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX .useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one