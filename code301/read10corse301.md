## The JavaScript Call Stack - What It Is and Why It's Necessary
What is a ‘call’?
✔ function invocation 
How many ‘calls’ can happen at once?
✔ single-threaded
What does LIFO mean?
✔ Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack?
1. When secondFunction() gets executed, an empty stack frame is created. It is the main (anonymous) entry point of the program.
2. secondFunction() then calls firstFunction()which is pushed into the stack.
3. firstFunction() returns and prints “Hello from firstFunction” to the console.
4. firstFunction() is pop off the stack.
5. The execution order then move to secondFunction().
6. secondFunction() returns and print “The end from secondFunction” to the console.
7. secondFunction() is pop off the stack, clearing the memory.

### ***What causes a Stack Overflow?***

- It's happened when there is a recursive function `a function that calls itself` without an exit point.


## **JavaScript error messages**

### ***What is a `refrence error`?***

- It's means that when you try to use a variable that is not yet declared you get this type os errors.

### ***What is a `syntax error`?***

- It's means  when you have something that cannot be parsed in terms of syntax.

### ***What is a `range error`?***

- It's means when you  invalid length to an object with some kind of length.

### ***What is a `tyep error`?***

- It's means when the types `number, string .....` you are trying to use or access are incompatible.

### ***What is a breakpoint?***

- It's means putting a debugger statement in your code in the line you want to break.

### ***What does the word `debugger` do in your code?***


- Debugging is the process of detecting and removing of existing and potential errors in the code by using the `console.log()` the variables you want to check.
