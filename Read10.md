# Stacks and Queues

## A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

## Common terminology for a stack is :
* Push 
* Pop
* Peek
* IsEmpty

**FILO mean : This means that the first item added in the stack will be the last item popped out of the stack.**

**LIFO mean :This means that the last item added to the stack will be the first item popped out of the stack.**

**Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time
no matter how many Nodes (n) you have in the stack.**

**Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will 
be re-assigned to the Node that lives below and the top Node is returned to the user**

## In the queue only two operations are allowed
### Enqueue and dequeue. 
**Enqueue means to insert an item into the back of the queue, dequeue means removing the front item. The picture
demonstrates the FIFO access. The difference between stacks and queues is in removing.**

**When you add an item to a queue, you use the enqueue action. This is done with an O(1) operation in time because it
does not matter how many other items live in the queue (n); it takes the same amount of time to perform the operation.**

**When you remove an item from a queue, you use the dequeue action. This is done with an O(1) operation in time 
because it doesn’t matter how many other items are in the queue, you are always just removing the front Node of the queue.**

![image](https://dunglai.github.io/public/post-assets/DataStructure/StackAndQueue/fig1.PNG)
