# Queue

# THEORY
The queue is a basic data structure just like a stack. In contrast to stack that uses the LIFO approach, queue uses the FIFO (first in, first out) approach. With this approach, the first item that is added to the queue is the first item to be removed from the queue. Just like Stack, the queue is also a linear data structure.

In a real-world analogy, we can imagine a bus queue where the passengers wait for the bus in a queue or a line. The first passenger in the line enters the bus first as that passenger happens to be the one who had come first.

# Basic Operations

The queue data structure includes the following operations:

EnQueue: Adds an item to the queue. Addition of an item to the queue is always done at the rear of the queue.

DeQueue: Removes an item from the queue. An item is removed or de-queued always from the front of the queue.

isEmpty: Checks if the queue is empty.

isFull: Checks if the queue is full.

peek: Gets an element at the front of the queue without removing it.

![image](https://github.com/prishakhemani/Queue/assets/142494518/603e1762-ca6c-48ec-a1e1-b78e8871cef0)

This is an empty queue and thus we have rear and empty set to -1.

Next, we add 1 to the queue and as a result, the rear pointer moves ahead by one location.

![image](https://github.com/prishakhemani/Queue/assets/142494518/0c4d69c5-2913-4e16-b6ae-1675da5dd5bc)

In the next figure, we add element 2 to the queue by moving the rear pointer ahead by another increment

![image](https://github.com/prishakhemani/Queue/assets/142494518/ab873fdb-37a1-490c-83e4-76aea8890dcb)

In the following figure, we add element 3 and move the rear pointer by 1.

![image](https://github.com/prishakhemani/Queue/assets/142494518/7fbdfd2f-1431-49c9-808d-f983c7cee132)

At this point, the rear pointer has value 2 while the front pointer is at the 0th location.

Next, we delete the element pointed by the front pointer. As the front pointer is at 0, the element that is deleted is 1.

![image](https://github.com/prishakhemani/Queue/assets/142494518/6142d511-07df-4d22-86be-dd5e03da0bc6)

Thus the first element entered in the queue i.e. 1 happens to be the first element removed from the queue. As a result, after the first dequeue, the front pointer now will be moved ahead t0 the next location which is 1.

# Applications

1)The queue data structure is used in various CPU and disk scheduling. Here we have multiple tasks requiring CPU or disk at the same time. The CPU or disk time is scheduled for each task using a queue.

2)The queue can also be used for print spooling wherein the number of print jobs is placed in a queue.




