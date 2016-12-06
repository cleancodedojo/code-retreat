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


## references
* Groner, Loiane. Learning JavaScript Data Structures and Algorithms - Second Edition.