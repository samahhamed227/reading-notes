## Linked Lists
A Linked List is a sequence of Nodes that are connected/linked to each other.


### What does it look like?
![linkedlist](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG)

## Traversal:
You are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. 
- The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null.
 
### Why do we use structure in linked list?
Structure in linked list is used to store data of the node as well as the pointer to the next node's address. A linked list is a linear collection of similar data where the next node is reached using the previous node in list.

### What is the use of structure in linked list?
In C programming, we use structures to create a linked list. The structure is a data type inside which we can define variables with different data types (e.g., int , char , pointer , etc.)


### How structure is used in linked list?
1. Insert node at the beginning.
2. Insert node in the middle
3. Insert node at the end

## What even is Big O?
Whether you’re building software as a service, choosing a front end framework, or just trying to make your code DRY and more elegant, that’s what all of us are striving towards: being efficient with our software, and choosing things that are important to what we’re building, all while being aware of the tradeoffs that we’ll ultimately have to make.
 > There are two major points to consider when thinking about how an algorithm performs: how much time it requires at runtime given how much time and memory it needs.



 ## Growing a linked list : 
 * Inserting an element at the beginning of a linked list is particularly nice and efficient because it takes the same amount of time, no matter how long our list is, which is to say it has a space time complexity that is constant, or O(1).
1. First, we find the head node of the linked list.
2. Next, we’ll make our new node, and set its pointer to the current first node of the list.
3. Lastly, we rearrange our head node’s pointer to point at our new node.

* But inserting an element at the end of a linked list is a different story. The interesting thing here is that the steps you take to actually do the inserting are the exact same:
1. Find the node we want to change the pointer of (in this case, the last node)
2. Create the new node we want to insert and set its pointer (in this case, to null)
3. Direct the preceding node’s pointer to our new node



### Example of Linked List !!
![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2014/03/DLL1.png)


### a diagram
![](https://i.ytimg.com/vi/pBrz9HmjFOs/maxresdefault.jpg)

### a map 
![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190621160855/Detect-loop-in-a-linked-list.png)