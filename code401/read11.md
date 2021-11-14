## **Event Driven Applications**

### ***Why is access control important?***

- Because `access controls` limit access to information and information processing systems. When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach. 

### ***Describe an application that would need access control.What is a role used for?***

- Role-based access control `RBAC`, also known as role-based security, is a mechanism that restricts system access. It involves setting permissions and privileges to enable access to authorized users.
- Most large organizations use role-based access control to provide their employees with varying levels of access based on their roles and responsibilities.
- This protects sensitive data and ensures employees can only access information and perform actions they need to do their jobs.

### *** What is a role used for?

The role determines which permissions the system grants to the user. 


### *** Why is role based access control more scalable than discretionary or mandatory access control?

Access control systems can be physical, limiting access to buildings, rooms, or servers, or they can be logical, controlling digital access to data, files, or networks.**



-----------------------------------------------

## **Terms**

- **Authorization** : It’s a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features.

 allows the user to access the various resources based on the user’s identity

- **Role Based Access Control** : Role-based access control (RBAC) restricts network access based on a person’s role within an organization and has become one of the main methods for advanced access control.


- **Capabilities** : A capability is a communicable, unforgeable token of authority. It refers to a value that references an object along with an associated set of access rights.

## Which 3 things had you heard about previously and now have better clarity on?

1. deferent between ACL and RBAC
2. why we use ACL 
3. why we use RABC

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

1. using RABC in our class
2. learn more about setting the role
3. how to make ACL easier to the user 

## What are you most excited about trying to implement or see how it works?
- sending the token automatically with every request 

# Event Driven Programming


- **events** : it is the process that will be done when you click or make any command to do something.
- events based on two things :

  - ***1- event handler*** : or call back function, that will run when click on the event.
  - ***2- event or main loop*** : that will sort the orders and run the correct function for the correct clicked event .

- ***3- ventEmitter*** : it is a module from node.js that allows us to use event driven programming, by built in events and functions.

- we can remove any event that we used from EventEmitter by "remveeventlistner" method. most reasons to remove any event are performance reasons when the event become useles or no need to use it.
