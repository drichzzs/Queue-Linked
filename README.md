# Queue-Linked

This code defines a Java class called MyQueueLinked that represents a queue data structure using a linked list.

A queue is a data structure that allows you to add elements to the end of the queue (enqueue) and remove elements from the front of the queue (dequeue) in a First-In, First-Out (FIFO) manner. This means that the first element you added to the queue will be the first one you remove.

The MyQueueLinked class has four instance variables: head, which is a reference to the front of the queue; tail, which is a reference to the end of the queue; count, which is an integer that keeps track of the number of elements in the queue; and data, which is an object that stores the data associated with the node.

The MyQueueLinked class has several methods:

isFull(): This method always returns false because the queue has no fixed size and therefore can never be full.

isEmpty(): This method returns true if the queue is empty and false otherwise.

enqueue(Object item): This method adds an element to the end of the queue.

peek(): This method returns the element at the front of the queue without removing it.

dequeue(): This method removes and returns the element at the front of the queue.

clear(): This method removes all elements from the queue.

size(): This method returns the number of elements in the queue.

toString(): This method returns a string representation of the elements in the queue.

The MyQueueLinked class also includes a main method that creates an instance of the MyQueueLinked class and adds a few elements to it using the enqueue method. It then removes and prints the first element using the dequeue method and prints the remaining elements using the toString method.

<img src="https://aldrich.smokyz01.repl.co/a4.png"/>
