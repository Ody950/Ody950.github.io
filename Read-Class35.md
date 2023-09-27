
# Graphs



## why this topic matters as it relates to what Iam studying in this module?

We can use graphs in .NET development to be applied to a number of different problems. It is possible to use them to represent dependencies between components in a software system. In this way, we as developers can gain a better understanding of the structure of the system and identify potential problems.  

## Summary

Graphs are pictorial representations of sets of objects interconnected by links. Points that represent interconnected objects are called vertices, and the links that join these vertices are called edges.



## Common Terms
- Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- Edge - An edge is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- Degree - The degree of a vertex is the number of edges connected to that vertex.



## Basic Primary Operations Of A Graph 

- Add Vertex − Adds a vertex to the graph.

- Add Edge − Adds an edge between the two vertices of the graph.

- Display Vertex − Displays a vertex of the graph.



## Traversals

* The traversal itself is like those of trees. 

### Depth First Search

When a dead end occurs in an iteration, the algorithm traverses the graph in a depth-first manner and uses a stack to keep track of the next vertex.

In order to accomplish this, it follows the following rules: 

* 1 − Visit the adjacent unvisited vertex. Mark it as visited. Display it. Push it in a stack.

* 2 − If no adjacent vertex is found, pop up a vertex from the stack. (It will pop up all the vertices from the stack, which do not have adjacent vertices.)

* 3 − Repeat Rule 1 and Rule 2 until the stack is empty.

### Breadth First Search
During each iteration of the algorithm, the algorithm traverses the graph in breadthward motion and uses a queue to remember to get the next vertex to begin the search when a dead end occurs.
In order to accomplish this, it follows the following rules: 

* 1 − Visit the adjacent unvisited vertex. Mark it as visited. Display it. Insert it in a queue.

* 2 − If no adjacent vertex is found, remove the first vertex from the queue.

* 3 − Repeat Rule 1 and Rule 2 until the queue is empty.




## How graphs are used in the real world


1. GPS and Mapping
2. Social Networks
3. Netflix uses graphs for suggestions of products

