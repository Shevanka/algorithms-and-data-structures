# Linked List

## Concept Overview

A linked list is a linear data structure where elements (nodes) are stored non-contiguously in memory.
Each node contains data and a reference (pointer) to the next node in the sequence.

Unlike arrays, linked lists do not require continuous memory allocation and allow efficient insertion
and deletion operations.

---

## Node Structure

A basic linked list node consists of:

- Data field
- Pointer to the next node

For doubly linked lists, each node also contains:

- Pointer to the previous node

---

## Types of Linked List

### Singly Linked List

- Each node points to the next node
- Traversal is one-directional

### Doubly Linked List

- Each node points to both previous and next nodes
- Allows bidirectional traversal
- Requires more memory due to extra pointer

---

## Core Operations

### Insertion

- Insert at the beginning
- Insert at the end
- Insert at a specific position

### Deletion

- Delete first node
- Delete last node
- Delete a specific node

---

## How It Works

- Nodes are dynamically allocated in memory
- The `head` pointer stores the address of the first node
- Traversal continues until a node points to `NULL`

---

## Use Cases

- Dynamic data storage
- Implementing stacks and queues
- Graph adjacency lists
- Memory-efficient insert/delete operations

---

## Complexity Analysis

### Time Complexity

| Operation               | Complexity |
| ----------------------- | ---------- |
| Access                  | O(n)       |
| Search                  | O(n)       |
| Insert (known position) | O(1)       |
| Delete (known position) | O(1)       |

### Space Complexity

- O(n), due to additional pointer storage per node

---

## Advantages

- Dynamic size
- Efficient insertions and deletions
- No memory reallocation needed

---

## Limitations

- No random access
- Extra memory usage for pointers
- Traversal is slower compared to arrays

---

## Variations / Related Concepts

- Circular Linked List
- Stack (linked list based)
- Queue (linked list based)
- Tree and graph node structures

---

## Implementation Notes

- Pointer manipulation must be handled carefully
- Edge cases include empty list and single-node list
- Memory deallocation is critical in low-level languages

---

## Learning Reflection

- Pointer handling was initially confusing, especially during delete operations
- Visualizing node connections significantly improved understanding
- Linked List concepts helped in understanding stack and queue implementations

---

## Status

**In Progress**
