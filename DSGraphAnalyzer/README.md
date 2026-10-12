# Data Structure and Graph Performance Analyzer

**Module:** CIT300 Data Structures and Algorithms – Graded Practical Assignment 2
**Language:** Java (console application)

## Project Description
A menu-driven console application demonstrating arrays, stacks, queues, linked lists,
searching (linear vs binary), a graph (BFS/DFS), and a performance comparison based on steps and execution time.

## Team Members
> Fill in for EVERY member (marks are deducted for missing/incorrect details).

| Student Name | Student ID | Assigned Responsibility | Individual Contribution |
|--------------|------------|-------------------------|-------------------------|
| (Full name)  | (ID)       | (e.g. Linked List)      | - (list what you implemented) |
| (Full name)  | (ID)       |                         | - |
| (Full name)  | (ID)       |                         | - |

## Technologies Used
Java (JDK 17+), Git/GitHub, VS Code

## Main Features
- Array: insert, insert at index, delete, search, display
- Stack: push, pop, peek, display (empty/full handling)
- Queue: enqueue, dequeue, front, display (circular array, empty/full handling)
- Linked List: insert front/end, delete, search, display
- Searching: linear, binary, and side-by-side comparison with steps and time
- Graph (adjacency list): add vertex, add edge, display, BFS, DFS
- Performance comparison table and "Display All Results"
- Input validation on every prompt

## How to Run
```bash
cd src
javac *.java
java Main
```

## File Overview
| File | Purpose |
|------|---------|
| Main.java | Main menu / integration |
| ArrayOps.java | Array component |
| StackOps.java | Stack component |
| QueueOps.java | Queue component |
| LinkedListOperations.java | Linked list component |
| SearchOps.java | Linear and binary search |
| Graph.java | Graph, BFS, DFS |
| PerformanceAnalyzer.java | Performance comparison |
| Results.java | Stores results for menu option 8 |
| InputUtil.java | Validated input helper |
