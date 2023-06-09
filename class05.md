# Linked List

## what is a linked list?

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers.

## analogy

A linked list is like a train. Each car is a node. The node contains the data and a pointer to the next node. The last car has a pointer to null.

## why linked list?

- Dynamic size
- Ease of insertion/deletion

## types of linked list

- Singly Linked List
- Doubly Linked List
- Circular Linked List

## singly linked list

A linked list is a sequence of data structures, which are connected together via links.

Each data structure contains two items: the data and a reference (in other words, a link) to the next data structure in the sequence. The last data structure has a link to a null value.

![singly linked list](https://www.tutorialspoint.com/data_structures_algorithms/images/linked_list.jpg)

## complicity related to array

| Operation | Array | Linked List |
|-----------|-------|-------------|
| Access    | O(1)  | O(n)        |
| Search    | O(n)  | O(n)        |
| Insertion | O(n)  | O(1)        |
| Deletion  | O(n)  | O(1)        |



## Some definitions

- **Head**: The first node in a linked list.
- **Tail**: The last node in a linked list.
- **Current**: The node that is currently being looked at.
