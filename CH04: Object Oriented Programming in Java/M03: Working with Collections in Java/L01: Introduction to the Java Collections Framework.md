## Introduction to the Java Collection Framework

### What you will learn

- Define the purpose of a collection
- Explain the purpose of the Java Collections Framework
- Compare several types of collections that are part of the Java Collections Framework
- Explain how to use the ArrayList and LinkedList Collections
- Discuss how to use a set collection
- Describe how to use a map collection

### The purpose of a collection

- A collection is a group of objects
- Java collections manage aggregate data
    - Store
    - Retrieve
    - Manipulate
    - Communicate

### What is the Java Collections Framework

- Allows developers to work with groups of objects
- Provides a set of classes and interfaces


### Types of Java Collections

| Types | Collection Types | Capabilities | Common Implementations |
| --- | --- | --- | --- |
| Lists | Ordered | <ul><li>Allow duplicate elements</li><li>Maintain order</li></ul>| <ul><li>ArrayList</li><li>LinkedList</li></ul> |
| Sets | Unordered | <ul><li>Do not allow duplicate elements</li><\ul> | <ul><li>HashSet</li><li>TreeSet</li></ul> |
| Maps | Unordered | <ul><li>Key-value pairs where each key is unique</li></ul> | <ul><li>HashMap</li><li>TreeMap</li></ul>|

### Using an array list

- Uses a dynamic array
- Allow fast random access
- Adds and removes middle elements more slowly

### Using a LinkedList array

- Uses a doubly linked list to store elements
- Adds and removes elements efficiently
- Accesses elements by index more slowly 

### Using Set collections

| A HashSet | A TreeSet |
| --- | --- |
| Does not maintain any order | Maintains a sorted order | 
| Allows null values | Does not allow null values | 


### Using Map collections HashMaps

Stores key-value pairs
- Each key must be unique
- Values can be duplicated

HashMap
- Allows null vlaues
- No guaranteed order

TreeMap
- Allows null values
- Maintains keys in a sorted order

### Recap

- Java collections store, retrieve, manipulate and communicate aggregate data.
- The Java Collections Framework is a powerful Java tool that allows developers to work with groups of objects.
- A **List** is an ordered collection that allows duplicate elements and mainatin order.
- A **Set** is an unordered collection that does not allow duplicate elements.
- A **Map** is an unordered collection of key-value pairs where each key is unique Common implementations include using a HashMap or a TreeMap
- An **ArrayList**, which uses a dynamic array to store elements, supports fast random access but operates more slowly when adding or removing elements from the middle.
- A **LinkedList** array stores elements in a doubly linked list and efficiently adds and removes elements but operates slowly when accessing elements by index.
- A **HashSet** does not maintain an order and allows null values
- A **TreeSet** maintains a soreted order of elements and does not allow null values
- A **Map** associate unique keys with values
- When you use a **HashMap** and a **TreeMap** allow null values
- When you use a **HashMap**, the data exists without a guaranteed order.
- A **TreeMap** maintains keys in sorted order.
