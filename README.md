# Data Structures and Algorithms

## Introduction

Data structures and algorithms are fundamental concepts in computer science that form the building blocks for efficient problem solving and software development. A solid understanding of DSA is crucial for writing optimized code, improving program performance, and excelling in technical interviews.

This document provides an in-depth overview of common data structures, key algorithms, time complexity analysis, and other important DSA concepts. We'll explore the theoretical foundations as well as practical implementations and applications.
----------------------------------------------------------------------------------------------------------------------------

## Data Structures

Data structures are ways of organizing and storing data so that it can be accessed and worked with efficiently. They define the relationship between data, and the operations that can be performed on the data.

### 1- Arrays

An array is a collection of elements stored at contiguous memory locations. It is the simplest and most widely used data structure.

Key characteristics:
- Fixed size (in most programming languages)
- Elements are accessed using an index
- Contiguous memory allocation

Operations and time complexities:
- Access: O(1) 
- Search: O(n)
- Insertion: O(n)
- Deletion: O(n)



### 2- Linked Lists

A linked list is a linear data structure where elements are stored in nodes. Each node contains a data field and a reference (link) to the next node in the sequence.

Types:
1. Singly Linked List
2. Doubly Linked List
3. Circular Linked List

Operations and time complexities:
- Access: O(n)
- Search: O(n)
- Insertion: O(1)
- Deletion: O(1)



### 3- Stacks

A stack is a linear data structure that follows the Last-In-First-Out (LIFO) principle. The last element inserted into the stack is the first one to be removed.

Key operations:
- Push: Add an element to the top
- Pop: Remove the top element
- Peek: View the top element without removing it

Time complexity for all operations: O(1)



### 4- Queues

A queue is a linear structure which follows the First-In-First-Out (FIFO) principle. The first element inserted into the queue is the first one to be removed.

Key operations:
- Enqueue: Add an element to the rear
- Dequeue: Remove the front element
- Front: Get the front element

Time complexity for all operations: O(1)



### 5- Trees

A tree is a hierarchical data structure consisting of nodes connected by edges. It has a root node and subtrees of children with a parent node.

Types:
1. Binary Tree
2. Binary Search Tree (BST)
3. AVL Tree
4. Red-Black Tree
5. B-Tree

Operations and time complexities (for a balanced BST):
- Search: O(log n)
- Insertion: O(log n)
- Deletion: O(log n)



### 6- Graphs

A graph is a non-linear data structure consisting of vertices and edges. The vertices are sometimes also referred to as nodes and the edges are lines or arcs that connect any two nodes in the graph.

Types:
1. Directed Graph
2. Undirected Graph
3. Weighted Graph

Common representations:
- Adjacency Matrix
- Adjacency List


### 7- Hash Tables

A hash table is a data structure that implements an associative array abstract data type, a structure that can map keys to values. It uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found.

Time complexity (average case):
- Search: O(1)
- Insertion: O(1)
- Deletion: O(1)


----------------------------------------------------------------------------------------------------------------------------

## Algorithms

An algorithm is a step-by-step procedure or formula for solving a problem. It is the foundation for all computer programming and is essential for efficient problem-solving.

### 1- Sorting Algorithms

Sorting algorithms arrange elements in a specific order (usually ascending or descending).

1. Bubble Sort
   - Time complexity: O(n^2)
   - Space complexity: O(1)

2. Selection Sort
   - Time complexity: O(n^2)
   - Space complexity: O(1)

3. Insertion Sort
   - Time complexity: O(n^2)
   - Space complexity: O(1)

4. Merge Sort
   - Time complexity: O(n log n)
   - Space complexity: O(n)

5. Quick Sort
   - Time complexity: O(n log n) average, O(n^2) worst case
   - Space complexity: O(log n)

6. Heap Sort
   - Time complexity: O(n log n)
   - Space complexity: O(1)

Sorting Algorithms Comparison

### 2- Searching Algorithms

Searching algorithms are designed to check for an element or retrieve an element from any data structure where it is stored.

1. Linear Search
   - Time complexity: O(n)

2. Binary Search
   - Time complexity: O(log n)

3. Depth-First Search (DFS)
   - Time complexity: O(V + E) where V is the number of vertices and E is the number of edges

4. Breadth-First Search (BFS)
   - Time complexity: O(V + E)



### 3- Graph Algorithms

1. Dijkstra's Algorithm (Shortest Path)
   - Time complexity: O((V + E) log V) with binary heap

2. Bellman-Ford Algorithm (Shortest Path with negative edges)
   - Time complexity: O(VE)

3. Floyd-Warshall Algorithm (All-pairs shortest path)
   - Time complexity: O(V^3)

4. Kruskal's Algorithm (Minimum Spanning Tree)
   - Time complexity: O(E log E) or O(E log V)

5. Prim's Algorithm (Minimum Spanning Tree)
   - Time complexity: O((V + E) log V) with binary heap



### 4- Dynamic Programming

Dynamic Programming is an algorithmic paradigm that solves a given complex problem by breaking it into subproblems and stores the results of subproblems to avoid computing the same results again.

Examples:
1. Fibonacci Series
2. Knapsack Problem
3. Longest Common Subsequence
4. Matrix Chain Multiplication

### 5- Greedy Algorithms

A greedy algorithm is an algorithmic paradigm that follows the problem-solving heuristic of making the locally optimal choice at each stage.

Examples:
1. Fractional Knapsack Problem
2. Huffman Coding
3. Prim's and Kruskal's algorithms for Minimum Spanning Tree

----------------------------------------------------------------------------------------------------------------------------

## Time Complexity Analysis

Time complexity is a way to represent the amount of time required by the program to run till its completion. It's generally calculated as a function of input size.

### 1- Big O Notation

Big O notation is used to classify algorithms according to how their run time or space requirements grow as the input size grows.

Common time complexities:
- O(1): Constant time
- O(log n): Logarithmic time
- O(n): Linear time
- O(n log n): Linearithmic time
- O(n^2): Quadratic time
- O(2^n): Exponential time



### 2- Space Complexity

Space complexity is a measure of how much working storage an algorithm needs.

----------------------------------------------------------------------------------------------------------------------------


## Advanced Topics

### 1- Balanced Trees

Balanced trees are a type of tree data structure where the height of the left and right subtrees of every node differs by at most one.

Examples:
1. AVL Trees
2. Red-Black Trees
3. B-Trees

### 2- Trie

A trie, also called digital tree or prefix tree, is a kind of search tree—an ordered tree data structure used to store a dynamic set or associative array where the keys are usually strings.



### 3- Segment Trees

A Segment Tree is a data structure that allows answering range queries over an array effectively, while still being flexible enough to allow modifying the array.

### 4- Fenwick Tree (Binary Indexed Tree)

A Fenwick tree or binary indexed tree is a data structure that can efficiently update elements and calculate prefix sums in a table of numbers.

