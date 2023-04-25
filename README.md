# Queue

 A queue is essentially a linear data structure for managing and storing data components. It adheres to the First In First Out (FIFO) principle.The first element added to an array in a queue is also the first element withdrawn from the array.There is an open queue at both ends. There are two ends: one for inserting data and the other for removing it.
 
 ## Operations Associated with a Queue in C:
 
 An abstract data structure called a queue offers the following methods for manipulating the data elements:
isEmpty(): To check if the queue is empty

isFull(): To check whether the queue is full or not

dequeue(): Removes the element from the frontal side of the queue

enqueue(): It inserts elements to the end of the queue

Front: Pointer element responsible for fetching the first element from the queue

Rear: Pointer element responsible for fetching the last element from the queue

## Working of Queue Data Structure:

1.The First-In-First-Out order is used in queues. The first element gets taken out of the list of items first.

2.The first and final elements in the queue are tracked by the front and rear pointers.

3.The queue must initially be initialised by setting Front = -1 and Rear = -1.

4.We must determine whether the queue is already full before inserting the element (enqueue), i.e., determining whether Overflow is present. We must move the element to the Rear pointer variable's location and increase the value of the Rear index by 1 if the queue is not full. We must set the value of Front to 0 before adding the first piece to the queue.

![image](https://user-images.githubusercontent.com/91966097/234374922-39488900-ec29-4c14-9a8a-fcffeaaf4a79.png)
