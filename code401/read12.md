## **Socket.io**

### ***What Socket.IO is***

- `Socket.IO` is a library that enables real-time, bidirectional and event-based communication between `the browser and the server`. It consists of:

   1. a Node.js server: Source|API
   2. a Javascript client library for the browser (which can be also run from Node.js): Source|API

### ***What is the benefit of transforming data into packets?***

- `TDM`-based networks must transform into `packet-based networks` to meet the demands of pervasive data-centric applications and services.

- `Packet-based` networks not only enable `new innovations, services, and business opportunities`, they are also the most `cost-effective, efficient, and scalable networks` for content delivery.

### ***UDP is often refereed to as a connectionless protocol. Why is this?***

- Because it is analogous to sending a letter where you don't acknowledge receipt.

### ***Can a socket server application have multiple socket connections?***

- Yes, Multiple connections on the same server can share the same `server-side IP/Port` pair as long as they are associated with different `client-side IP/Port` pairs, and the server would be able to handle as many clients as available system resources allow it to.

### ***Can a socket connection application be connected to multiple socket servers?***

-  No,a server socket listens on a single port. All established client connections on that server are associated with that same listening port on the server side of the connection.

### ***Can an application be both a socket server and a socket connection?***

- No, You can not combine server and client sockets into one, because a TCP/IP connection goes from a source port to a destination port, with each having unique port numbers.


| Term       |       Definition             |
| -----------|------------------------------|
|Observer Pattern|The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.|
|Listener|An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.|
|Event Handler|Event handling (overview) Events are signals fired inside the browser window that notify of changes in the browser or operating system environment. Programmers can create event handler code that will run when an event fires, allowing web pages to respond appropriately to change.|
|Event Driven Programming|In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.|
|Event Loop|In computer science, the event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program|
|Event Queue|An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system|
|Call Stack|“Since the Call Stack is organized as a stack, the caller pushes the return address onto the stack, and the called subroutine, when it finishes, pulls or pops the return address off the Call Stack and transfers control to that address.|
|Emit/Raise/Trigger|emit --> The emit method (the publish method), on the other hand, allows you to "emit" an event, which causes all callbacks registered to the event to 'fire', (get called). Short: Emit's job is to trigger named event(s) which in turn cause functions called listeners to be called ... raise -->/Fire the event document. dispatchEvent(event) .. trigger-->The trigger() method triggers the specified event and the default behavior of an event (like form submission) for the selected elements. This method is similar to the triggerHandler() method, except that triggerHandler() does not trigger the default behavior of the event|Subscribe|As a publisher, you create an Observable instance that defines a subscriber function. ... To execute the observable you have created and begin receiving notifications, you call its subscribe() method, passing an observer. This is a JavaScript object that defines the handlers for the notifications you receive|database|PouchDB is an open-source JavaScript database inspired by Apache CouchDB that is designed to run well within the browser. PouchDB was created to help web developers build applications that work as well offline as they do online|