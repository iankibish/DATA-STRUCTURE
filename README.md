QUESTION 2
 
 Linear Data Structures
1. Arrays
Where Applied

Image processing systems (pixel grids)

Scientific computing libraries like NumPy

Database record storage

Game development (grid-based maps)

Why Arrays Are Used

O(1) fast indexing – Direct access using index

Memory efficiency – Stored in contiguous memory

CPU cache-friendly – Improves performance

Best for fixed-size data collections

Real Example

In Adobe Photoshop, images are stored as large 2D arrays of pixels.

2. Linked Lists
Where Applied

Music playlists

Browser navigation

Memory management in operating systems

Why Linked Lists Are Used

Dynamic size – No fixed memory limit

Efficient insertion and deletion

Does not require contiguous memory

Real Example

Used in process scheduling within Linux for dynamic task handling.

3. Stacks
Where Applied

Function call management (Call Stack)

Undo/Redo systems

Expression evaluation (compilers)

Why Stacks Are Used

LIFO (Last In First Out) behavior

Natural fit for recursion

Easy reversal of operations

Real Example

Undo feature in Microsoft Word uses a stack to reverse actions.

4. Queues
Where Applied

CPU task scheduling

Printer spooling systems

Network packet handling

Message brokers

Why Queues Are Used

FIFO (First In First Out) fairness

Efficient task ordering

Prevents starvation in systems

Real Example

Distributed streaming platform Apache Kafka uses queue-like logs for message ordering.

2. Non-Linear Data Structures
5. Trees
Where Applied

File systems

Databases indexing

XML/HTML DOM structure

Artificial Intelligence (decision trees)

Why Trees Are Used

Represent hierarchical relationships

Fast searching and sorting (O(log n))

Efficient indexing with B-Trees

Real Examples

MySQL uses B-Trees for indexing.

File systems in Windows use tree structures for directories.

6. Graphs
Where Applied

Social networks

GPS navigation

Network routing

Recommendation systems

Why Graphs Are Used

Represent complex relationships

Support shortest path algorithms (Dijkstra)

Efficient modeling of connected systems

Real Examples

Google Maps uses graphs for route calculation.

Facebook models friendships as graph connections.

7. Hash Tables
Where Applied

Caching systems

Database indexing

Password storage systems

Dictionaries in programming languages

Why Hash Tables Are Used

O(1) average lookup time

Efficient key-value storage

Fast search, insert, delete operations

Real Example

Redis uses hash tables for ultra-fast data retrieval.

3. Advanced Data Structures
8. Heaps (Priority Queues)
Where Applied

CPU scheduling

Task management systems

Pathfinding algorithms

AI systems

Why Heaps Are Used

Efficient priority management

O(log n) insertion and deletion

Always retrieves highest/lowest priority element

Real Example

Used in shortest path algorithms inside Google Maps.

9. Tries (Prefix Trees)
Where Applied

Autocomplete systems

Spell checkers

Search engines

Why Tries Are Used

Fast prefix searching

Efficient word storage

Reduces duplicate comparisons

Real Example

Search suggestions in Google Search use trie-like structures.

4. How Data Structures Work Within Systems
System	Data Structure Used	Why
Operating System	Queue, Stack, Tree	Process scheduling, memory management
Database	B-Tree, Hash Table	Fast indexing and searching
Web Browser	Stack, Tree, Hash Table	Navigation, DOM rendering, caching
Social Media	Graph	Relationship modeling
E-commerce	Hash Table, Tree	Fast product search
Key Reasons Data Structures Are Chosen

Performance Efficiency – Faster execution time

Memory Optimization – Better space management

Scalability – Handle millions of users/data

Problem-Specific Design – Each structure solves a specific problem efficiently

Conclusion

Data structures are applied based on:

Nature of the problem (hierarchical, linear, relational)

Required speed (search, insert, delete)

Memory constraints

System scalability requirements

They are the backbone of:

Operating systems

Databases

Web applications

AI systems

Networking platforms

   QUESTION 3
   1. Google Maps
Application

Google Maps

Data Structures Used

Graph (cities = nodes, roads = edges)

Heap (Priority Queue)

Algorithms Used

Dijkstra’s Algorithm

A* (A-Star) Algorithm

Why?

A road network is naturally a graph.

Dijkstra and A* efficiently compute the shortest path.

A heap allows fast selection of the next closest location (O(log n)).

Handles millions of locations efficiently.

2. Facebook
Application

Facebook

Data Structures Used

Graph (users as nodes, friendships as edges)

Hash Tables

Algorithms Used

Breadth-First Search (BFS) (friend suggestions)

Graph traversal algorithms

Recommendation algorithms

Why?

Social connections are best modeled as a graph.

BFS finds mutual friends efficiently.

Hash tables allow fast user data lookup (O(1)).

3. Google Search
Application

Google Search

Data Structures Used

Trie (Prefix Tree)

Hash Table

Inverted Index (Tree-based structure)

Algorithms Used

PageRank Algorithm

String matching algorithms

Why?

Trie enables fast autocomplete suggestions.

Inverted index enables quick keyword search.

PageRank ranks pages efficiently based on graph structure of the web.

4. Microsoft Word
Application

Microsoft Word

Data Structures Used

Stack

Algorithms Used

Undo/Redo operation logic

Why?

Stack follows LIFO principle.

Last action performed is the first action undone.

Efficient and simple implementation.

5. Linux Operating System
Application

Linux

Data Structures Used

Queue (Process scheduling)

Tree (File system hierarchy)

Linked List (Kernel data management)

Algorithms Used

Round Robin Scheduling

Completely Fair Scheduler (CFS)

Why?

Queue ensures fair process execution (FIFO).

Tree structure represents directory hierarchy.

Linked lists allow dynamic memory management.

6. MySQL Database
Application

MySQL

Data Structures Used

B-Tree

Hash Index

Algorithms Used

Binary Search

Indexing algorithms

Why?

B-Trees maintain sorted data for fast searching (O(log n)).

Efficient disk-based storage.

Optimized for large-scale databases.

7. YouTube
Application

YouTube

Data Structures Used

Graph

Heap

Hash Tables

Algorithms Used

Recommendation algorithms

Ranking algorithms

Search algorithms

Why?

Graph models user-video relationships.

Heap ranks trending videos.

Hash tables provide fast access to video metadata.

8. E-commerce Platforms (Amazon)
Application

Amazon

Data Structures Used

Hash Table

Tree

Graph

Algorithms Used

Search algorithms

Sorting algorithms

Recommendation algorithms

Why?

Hash tables allow fast product lookup.

Trees organize product categories.

Graphs connect users to products for recommendations.

9. Redis (Caching System)
Application

Redis

Data Structures Used

Hash Table

Sorted Sets

Lists

Algorithms Used

Hashing algorithms

LRU (Least Recently Used) Cache algorithm

Why?

O(1) data retrieval.

Sorted sets rank items efficiently.

LRU removes least used items to optimize memory.

10. Web Browsers (Google Chrome)
Application

Google Chrome

Data Structures Used

Tree (DOM structure)

Stack (Navigation)

Hash Table (Caching)

Algorithms Used

Parsing algorithms

Rendering algorithms

Why?

HTML structure is hierarchical → Tree.

Back/Forward buttons → Stack.

Cache lookup → Hash table for speed.

Summary Table
Application	Data Structure	Algorithm	Reason
Google Maps	Graph + Heap	Dijkstra/A*	Shortest path
Facebook	Graph	BFS	Friend suggestions
Google Search	Trie	PageRank	Fast search & ranking
MS Word	Stack	Undo logic	Reverse operations
Linux OS	Queue	Round Robin	Fair scheduling
MySQL	B-Tree	Binary Search	Fast indexing
YouTube	Graph + Heap	Ranking	Recommendations
Amazon	Hash Table	Sorting/Search	Fast product lookup
Redis	Hash Table	LRU	Fast caching
Chrome	Tree	Parsing	Page rendering
Conclusion

Applications choose data structures and algorithms based on:

Speed requirements

Data relationships

Memory efficiency

Scalability

Nature of the problem

Efficient systems rely on the correct combination of:

Data structure (how data is stored)

Algorithm (how data is processed)
