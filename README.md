# Data Structures II Assignments

This repository showcases my work as an undergraduate student at **Loyola University Chicago (LUC)** in **COMP 272: Data Structures II**. The assignments are implemented in Java and demonstrate how core data structures are designed, implemented, analyzed, and applied to practical problems.

## Data Structures Covered

The repository includes examples of the following structures and subcategories:

- **Linked lists**
	- Singly linked lists
	- Custom linked-list nodes and pointer-based traversal
- **Arrays**
	- Array-backed storage for tables, buckets, heaps, filters, and graph data
	- Multidimensional arrays where appropriate
- **Maps and key-value structures**
	- Custom hash maps
	- Hash tables with separate chaining
	- Hash tables with open addressing
	- Cuckoo hashing
- **Hashing and probabilistic structures**
	- Hash functions and collision handling
	- Bloom filters
	- Hash nodes and bucket-based storage
- **Trees**
	- Binary search trees (BSTs)
	- AVL trees
	- Red-black tree operations
	- Tree nodes and rotations
- **Heaps and priority queues**
	- Min-heaps
	- Array-backed priority queues
- **Graphs and composite structures**
	- Graph representations and traversal-related logic
	- Structures that combine trees, arrays, maps, and queues

Vectors and Java's built-in `Map` implementations are useful related concepts in the broader data-structures ecosystem. This repository focuses primarily on implementing the underlying structures directly, rather than treating library containers as black boxes.

## Assignment Overview

| Assignment | Main focus | Representative implementation |
| --- | --- | --- |
| `PA1` | Linked lists and nodes | Singly linked list operations |
| `PA2` | Binary search trees | Binary tree insertion, search, and traversal |
| `PA3` | Self-balancing trees | AVL tree and red-black tree problems |
| `PA4` | Hash tables and maps | Custom hash map, hash nodes, and collision handling |
| `PA5` | Advanced hashing | Bloom filter and Cuckoo hash table |
| `PA6` | Priority queues | Min-heap and heap-based problem solutions |
| `PA7` | Comprehensive application | AVL event scheduler, graph logic, and trending reports |

## Repository Structure

```text
PA1/  Singly linked lists
PA2/  Binary search trees
PA3/  AVL and red-black trees
PA4/  Hash tables and custom hash maps
PA5/  Bloom filters and Cuckoo hashing
PA6/  Min-heaps and priority queues
PA7/  Final integrated data-structures problems
```

## Running the Assignments

Each assignment is organized as its own Java source directory. From the repository root, compile an assignment and run its `Main` class when one is present:

```bash
javac PA1/*.java
java -cp PA1 Main
```

The same pattern can be used for `PA2`, `PA4`, `PA5`, and `PA6`. `PA3` and `PA7` contain their primary implementations in the Java files shown in their directories and may be compiled directly with:

```bash
javac PA3/*.java
javac PA7/*.java
```

## Learning Goals

Together, these assignments practice:

- Choosing an appropriate data structure for a problem
- Implementing core operations without relying solely on library abstractions
- Managing nodes, links, buckets, indices, and array-backed storage
- Handling collisions, balancing, ordering, and priority
- Comparing tradeoffs in time complexity, space usage, and practical behavior

This collection represents my growth throughout Data Structures II and the programming work I completed as an undergraduate at LUC.
