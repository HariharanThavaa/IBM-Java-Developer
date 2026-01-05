## Working with Lists

### What you will learn

- Define lists and describe. their features
- Identify the characteristics and use cases of ArrayLists and LinkedLists

### Introduction to lists

- Store ordered elements
- Allow duplicates
- Enable access to items

### Types of lists

- ArrayList 
- LinkedList


### ArrayList

- Uses a dynamic array
- Resizes automatically
- Facilitates fast access to elements
- Is unsuitable for frequent modication

### Arraylist: Applications

- Store items
- Include dynamic additions and removals
- Implement stack-like behavior
- Create dynamic arrays

### LinkedList 

- Uses a doubly linked list
- Enables fast insertions and deletions
- Offers dynamic resizing 
- Is ideal for queue operations

### LinkedList: Applications

- Implement queues
    - Add and remove elements from both ends
- Store previous state for undo functionalities
- Manage memory efficiently
    - Handle frequent insertions and deletions

### List selection

- ArrayList
    - Access elements quickly
    - Maintain a stable list size
- LinkedList
    - Add or remove elements frequently
    - Implement stacks or queues

### Comparison

ArrayList
- Storage: Uses a dynamic array
- Access speed: Faster
- Modification speed: Slower (shifting/resizing)
- Initial capacity: Default capacity of 10
- Best use case: Minimal modifications

LinkeList
- Storage: Uses doubly linked nodes
- Access speed: Slower (requires traversal)
- Modification speed: Faster (no shifting needed)
- Initial capacity: Starts empty
- Best use case: Frequent modifications


### Recap

- Lists in Java store ordered elements allow duplicates and provide access by position.
- ArrayLists use a dynamic array for storage, offering fast element access but slower modifications due to resizing and shifting.
- LinkedLists use a doubly linked list structure, allowing faster insertion and deletions but slower access due to sequential traversal. 
- ArrayLists are used in applications that require quick access and stable list sizes.

