# Component Based UI

## Name 5 Javascript UI Frameworks (other than React)

The 5 Most Popular JavaScript Frameworks

1. Node.js
Node.js is not exactly a JavaScript framework; it’s a runtime environment. While JavaScript can be written directly into the web browser, this is not always desirable.

This is why Node.js lends the capacity for command-line tools and server-side scripting.

Though JavaScript usually operates on the client-side or the front-end, server-side scripting begets faster load times as browser technology is not needed. This can decrease user frustration and increase SEO.

2. Vue.js
Vue.js calls itself the “progressive” JavaScript framework. The name stems from its philosophy of incremental adoption. In Vue.js, the core library is focused on the view layer only so any additional functionality must be adopted in increments.

The framework uses a model-view-viewmodel (MVVM) architectural pattern. This pattern separates the graphical user interface (UI) – or the view – from the business logic of the application – or the model. The viewmodel layer is a converter medium that synchronizes data.

3. AngularJS
AngularJS is maintained by Google and addresses common complications in building single-page applications (SPAs). This framework works by leveraging HTML vocabulary on dynamic web pages. In the past, HTML could only be used for static content.

SPAs work by dynamically loading content from the webserver rather than the web browser. As a result, SPAs function in a similar fashion to mobile applications and do not need to be reloaded.

4. Ember.js
Ember.js is a JavaScript framework employing a component-service pattern. Opposed to the traditional model-view-controller (MVC) architecture, components in Ember.js are central to the framework. Almost everything in Ember.js can be categorized as a service or component.

Components are transient and manipulate the markup text and styles of an application UI. Services are objects that live for the duration of an application. They can be made available for different parts of your applications and are best used for persistent states.

5. React
React is a JavaScript framework developed by Facebook that simplifies the process of building interactive UIs. It is the base of React Native, an adjacent framework for building mobile applications.

Both frameworks have a one-way data flow, which is considered more intuitive than bi-directional data binding. Hot reload is another popular feature of the React frameworks allowing developers to immediately see changes as they are applied.

## What’s the difference between a framework and a library?

A library performs specific, well-defined operations.

A framework is a skeleton where the application defines the "meat" of the operation by filling out the skeleton. The skeleton still has code to link up the parts but the most important work is done by the application.

A library is essentially a set of functions that you can call, these days usually organized into classes. Each call does some work and returns control to the client.

A framework embodies some abstract design, with more behavior built in. In order to use it you need to insert your behavior into various places in the framework either by subclassing or by plugging in your own classes. The framework's code then calls your code at these points.

Examples of libraries: Network protocols, compression, image manipulation, string utilities, regular expression evaluation, math. Operations are self-contained.

Examples of frameworks: Web application system, Plug-in manager, GUI system. The framework defines the concept but the application defines the fundamental functionality that end-users care about.

## Terms

| Term                            | Def                   |
| :-------------                  |   :----------         |
| Rendering|Javascript uses the document object model (DOM) to manipulate the DOM elements. Rendering refers to showing the output in the browser.|
|Templates|A template is a chunk of HTML that you need to inject onto the page. Often templates are created “server side” – in that they come to the JavaScript fully formed and just need to be put into the DOM. But sometimes that isn’t feasible or would require and extra round trip to the server which might be slow. In that case having the template right in JavaScript is ideal. You can certainly just do a bit of string concatenation adding together bits of HTML and data until you have the template you need. But that likely isn’t ideal as it doesn’t separate the concerns of data and template. Real JavaScript templating can help here.|
|State| State is a plain JavaScript object used by React to represent an information about the component’s current situation.It’s managed in the component (just like any variable declared in a function). The difference is while a “normal” variable “disappears” when their function exits, the state variables are preserved by React|