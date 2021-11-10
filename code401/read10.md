## **Stacks and Queues**

### ***What is a Stack***

- A stack is a data structure that consists of `Nodes`. Each `Node` references the `next Node` in the `stack`, but does not reference its previous.


>example of what a stack looks like:

![stack](https://open4tech.com/wp-content/uploads/2018/12/word-image.png)

-  As you can see, the topmost item is denoted as the `top`. When you `push` something `to the stack`, it becomes the `new top`. When you `pop` something `from the stack`, you `pop` the `current top` and set the `next top` as `top.next`.

### ***Push O(1)***


### ***What is a Queue***

### Common terminology for a stack

1. **Enqueue**: Nodes or items that are added to the queue.
2. **Dequeue**: Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
3. **Front**: This is the front/first Node of the queue.
4. **Rear**: This is the rear/last Node of the queue.
5. **Peek**: When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
6. **IsEmpty**: returns true when queue is empty otherwise returns false.

### ***Queues follow these concepts***

- **FILO**: `First In Last Out`,This means that the first item in the queue will be the first item out of the queue.
- **LIFO**: `Last In First Out`,This means that the last item in the queue will be the last item out of the queue.



>example of what a stack looks like:

![que](https://i0.wp.com/learnersbucket.com/wp-content/uploads/2019/01/Queue-2-1.png?fit=768%2C400&ssl=1)


### 3- What are Queues used for?
Queue, as the name suggests is used whenever we need to manage any group of objects in an order in which the first one coming in, also gets out first while the others wait for their turn.

### 4- What are Stacks used for?
Stacks are used to implement functions, parsers, expression evaluation, and backtracking algorithms. A pile of books, a stack of dinner plates, a box of pringles potato chips can all be thought of examples of stacks. The basic operating principle is that last item you put in is first item you can take out.



### 5- what is the difference between queues and Stacks?
Stacks are based on the LIFO principle, i.e., the element inserted at the last, is the first element to come out of the list. 

Queues are based on the FIFO principle, i.e., the element inserted at the first, is the first element to come out of the list. 
In queues we maintain two pointers to access the list.