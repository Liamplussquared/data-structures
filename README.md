
## Complexity of Data Structures

### Array / dynamic array
Elements laid out sequentially in memory. Constant time indexing, linear time searching. Dynamics arrays have logical size and a capacity, allow adding/removal.
Sorted arrays lead to O(log(n)) search 

### Linked lists
Adding at start is O(1) for singly linked. Removal at end is O(1) for doubly linked. Indexing in linear time.

### Binary search trees
Balanced BST ->  all operations are O(log n). Worst case (all left children or all right children) then all operations O(n)

### Hash table
aka map, dictionary.
Worst case -> searching when too many elements hashed into same key (array/linked list created, or jump again)
           -> hash table past load balance
Avoid O(n) complexity by choosing good hash function & have large table. 

## AVL tree
Balanced BST, rotations (O(1)) to make balanced. Maintain O(log n) complexity.

## Stack
LIFO

## Queue
FIFO



| Data structure | Indexing | Searching | Insertion | Removing | Space complexity |
|----------------|----------|-----------|-----------|----------|------------------|
| Array/dynamic  | O(1)     | O(n)      | O(n)      | O(n)     | O(n)             |
| Linked lists   | O(n)     | O(n)      | O(1)      | O(1)     | O(n)             |
| BST            | O(logn)/n| O(logn)/n | O(logn)/n | O(logn)/n| O(n log n)       |
| Hash table     | -        | O(1) / n  | O(1) / n  | O(1) / n | O(n)             |
| AVL tree       | O(logn)  | O(logn)   | O(logn)   | O(logn)  | O(logn)          |
| Stack / Queue  | O(n)     | O(n)      | O(1)      | O(1)     | O(n)             |
|                |          |           |           |          |                  |
|                |          |           |           |          |                  |