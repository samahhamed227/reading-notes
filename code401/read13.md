# READ 13 : Message Queues

![img](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

# Review, Research, and Discussion

## 1- What does it mean that web sockets are bidirectional? Why is this useful?

   *  it means communication flows both ways between a server and client

   *  this is useful because a conversation can be kept going between a server and client

   *  It enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time. In the context of networked AV and control systems, this allows devices to send and receive continuous streams of data to and from any point on the network.

## 2- Does socket.io use HTTP? Why?

    a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js ( to communication with clients.).


   ##  3-What happens when a server emits an event?

- It will send an event called message to the client, after the client connects. The send function on socket object associates the 'message' event.

### 4- What happens if a client “misses” an event?

- The events will be ignored 

### 5-How can we mitigate this?
 
- You could avoid missing messages by always having the handlers  and then deciding in the handlers whether to do anything with the message or not.


### 6-Sockets work based on events. There are some reserved events, which can be accessed using the socket object on the server side.These are :

1. Connect
2. Message
3. Disconnect
4. Reconnect
5. Ping
6. Join and
7. Leave.
### ***The client-side socket object also provides us with some reserved events, which are :***

1. Connect
2. Connect_error
3. Connect_timeout
4. Reconnect, etc.

## **Terms**

- **Socket**: it was created to use open connections to facilitate realtime communication, still a relatively new phenomenon at the time. 

- **Web Socket**:  it is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server.

- **Socket.io**: it is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

- **Client**: a computer hardware device or software that accesses a service made available by a server.

- **Server**: is a physical computer dedicated to run services to serve the needs of other computers. Depending on the service that is running, it could be a file server, database server, home media server, print server, or web server.

- **OSI Model**: `The Open Systems Interconnection (OSI)` model describes seven layers that computer systems use to communicate over a network.

- **TCP Model**:  `TCP` model defines how devices should transmit data between them and enables communication over networks and large distances. The model represents how data is exchanged and organized over networks.

- **TCP**: `TCP stands for Transmission Control Protocol` a communications standard that enables application programs and computing devices to exchange messages over a network. 

- **UDP**: `User Datagram Protocol, or UDP,` is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups.

- **Packets**: it is a small segment of a larger message.


# Preview

## Which 3 things had you heard about previously and now have better clarity on?

   TCP, OSI model, web sockets

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

   How to mitigate clients missing events, using socket.io with an api, broadcasting events

## What are you most excited about trying to implement or see how it works?

   A real-time chatroom or messaging queue