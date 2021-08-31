# React Docs - Forms

## What is a Controlled Component?
Controlled Components
In HTML, form elements such as < .input>, <.textarea>, and <.select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().



## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
*we wait to store the users responses from the form into state when they submit the form * because you need to write an event handler for every way your data can change and pipe all of the input state through a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library.

## How do we target what the user is entering if we have an event handler on an input field?
The event also applies to elements with contenteditable enabled, and to any element when designMode is turned on. In the case of contenteditable and designMode, the event target is the editing host. If these properties apply to multiple elements, the editing host is the nearest ancestor element whose parent isn't editable.

# The Conditional (Ternary) Operator Explained
## Why would we use a ternary operator?
Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms

## Rewrite the following statement using a ternary statement:
variable = (conditon) ?something :somethingelse4
# React Bootstrap - Forms

## Forms
HTML Form is a document which stores information of a user on a web server using interactive controls. An HTML form contains different kind of information such as username, password, contact number, email id etc. The elements used in an HTML form are check box, input box, radio buttons, submit buttons .

HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state. For example, this form in plain HTML accepts a single name

