### 1. Name 3 real world use cases where you’d want to change the request with custom middleware

- Handling error.
- Track user behavior and stored.
- Hight-level payment method security.

### 2. True or false: The route handler is middleware?

-  False

## 3. In what ways can a middleware function end the process and send data to the browser?
**If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.**

### 4- At what point in the request lifecycle can you “inject” middleware? 
After the request have been received.

### 5. ”What can cause express to error with “Request headers sent twice, cannot start a second response”

> when you send more than one request to the server and make interupt between this requests, the server will dell with this requests by send a response have an error.

---


| Term       |       Definition             |
| -----------|------------------------------|
|Middleware     |Middleware: are functions that have access to the request object `req`, the response object `res`, and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named `next`.|
| Request Object| is the main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object. The request object is application independent in that both servers and clients use the same Request class.|
| Response Object   | It is the object which communicates between the server and the output which is sent to the client.|
|Application Middleware   | is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.|
|Routing Middleware   |  It's means that the middleware functions can perform the following tasks:Execute any code,Make changes to the request and the response objects.|
|Test Driven Development  | is a software development process relying on software requirements being converted to test cases before software is fully developed, |
|Behavioral Testing |  is a structured study and analysis of a person’s behavior using various methods like interviews, direct supervision, and self-observation. 
|



#  Preview

Which 3 things had you heard about previously and now have better clarity on?error/testing/handler
Which 3 things are you hoping to learn more about in the upcoming lecture/demo? I don't have anything on my mind right now
What are you most excited about trying to implement or see how it works? I don't have anything on my mind right now