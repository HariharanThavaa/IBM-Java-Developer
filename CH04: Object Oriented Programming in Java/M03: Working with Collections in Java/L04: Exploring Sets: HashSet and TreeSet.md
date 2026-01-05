## Exploring Sets: HashSet and TreeSet

### What you will learn

- Describe HashSets and TreeSets, list their features, and explain their applications.
- Compare HashSets and TreeSets.
- Explain the decision criteria for set selection.

### Introduction

- Ensures data has no duplicates
- Keeps data organized

### Set

- Stores unique elements
- Ensures no duplicates
- Maintains a unique collection

### HashSet

- Enables constant time complexity for
    - Add
    - Remove
    - Contains
- Doesn't allow duplicates
- Offers fast performance
- Permits one null element
- Uses a hash table for storage
- Doesn't maintain element order

### TreeSet

- Implement a red-black tree structure
- Maintains a sorted order of elements based on their natural ordering or a specified comparator
- Does not allow duplicate elements
- Provides logarithmic time performance in (O(log n)) for basic operations
- Does not allow null elements

### TreeSet: Applications

- Stores sorted lists of data, such as names or dates.
- Implement range queries to find elements within a specific range.
- Manages scores or rankings that need to be sorted.

### HashSet vs TreeSet

**HashSet**
- No specific order
- Fast (quick operations)
- Does not allow duplicates
- Can store one null value
- Uses a hash table

**TreeSet**
- Elements are sorted
- Slower (operations take longer)
- Does not allow duplicates
- Cannot store null values
- Uses a balanced tree

### Recap

- A set is a data structure that stores unique elements, ensuring no duplicates and maintaining a collection of items without repetitions

- HashSet uses a hash table for storage, offering fast performance

- It doesn't store elements in any particular order.

- HashSet is ideal for storing unique user IDs, tracking items in inventory systems, and removing duplicates from lists.

- TreeSet maintains elements in sorted order using a red-black tree structure, ensuring logarithmic time performance for basic operations.

- It stores elements in a predefined order

- TreeSet is commonly used for storing sorted data, maintaining leaderboards, or managing ordered lists such as student grades or dates.

