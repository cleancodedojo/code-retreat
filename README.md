# code-retreat

## four rules of simple design
* tests pass
* expresses intent
* no duplication
* short

### kata

#### [conway's game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life#Rules)
* 1. any live cell with < 2 live neighbors dies of under population
* 2. any live cell with 2 or 3 live neighbors lives on
* 3. any live cell with > 3 live neighbors dies of over population
* 4. any dead cell with exactly 3 live neighbors comes alive

#### stack
* stack is an ordered collection of items that follows the LIFO (Last In First Out) principle.
* The addition of new items or the removal of existing items takes place at the same end.
* The end of the stack is known as the top, and the opposite side is known as the base.
* The newest elements are near the top, and the oldest elements are near the base.

##### methods
* push(element): This adds a new item to the top of the stack.
* pop(): This removes the top item from the stack. It also returns the removed element.
* peek(): This returns the top element from the stack. The stack is not modified (it does not remove the element;
it only returns the element for information purposes).
* isEmpty(): This returns true if the stack does not contain any elements,
and false if the size of the stack is bigger than 0.
* clear(): This removes all the elements of the stack.
* size(): This returns the number of elements that the stack contains. It is similar to the length property of an array.

#### queue
* queue is an ordered collection of items that follows the FIFO (First In First Out),
also known as the first-come first-served principle.
* The addition of new elements in a queue is at the tail, and the removal is from the front.
* The newest element added to the queue must wait at the end of the queue.

##### methods
* enqueue(element): This adds a new item at the back of the queue.
* dequeue(): This removes the first item from the queue (the item that is in the front of the queue).
It also returns the removed element.
* front(): This returns the first element from the queue, the first one added,
and the first one that will be removed from the queue. The queue is not modified (it does not remove the element;
it only returns the element for information purposes-very similar to the peek method from the Stack class).
* isEmpty(): This returns true if the queue does not contain any elements, and false if the queue is bigger than 0.
* size(): This returns the number of elements the queue contains. It is similar to the length property of the array.

#### linked list
* Linked lists store a sequential collection of elements; but unlike arrays, in linked lists,
the elements are not placed contiguously in memory.
* Each element consists of a node that stores the element itself and also a reference (also known as a pointer or link)
that points to the next element.

##### methods
* append(element): This adds a new item to the end of the list.
* insert(position, element): This inserts a new item at a specified position in the list.
* remove(element): This removes an item from the list.
* indexOf(element): This returns the index of the element in the list.
If the element is not in the list, it returns -1.
* removeAt(position): This removes an item from a specified position in the list.
* isEmpty(): This returns true if the linked list does not contain any elements and
false if the size of the linked list is bigger than 0.
* size(): This returns the number of elements the linked list contains.
It is similar to the length property of the array.
* toString(): As the list uses a Node class as an item,
we need to overwrite the default toString method inherited from the JavaScript object to output only the element values.

## references
* Groner, Loiane. Learning JavaScript Data Structures and Algorithms - Second Edition.