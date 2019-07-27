# Breadth First Search Using Python
# What is Breadth First Search

**Breadth First Traversal (or Search)** for a graph is similar to Breadth First Traversal of a tree.
The only catch here is, unlike trees, graphs may contain cycles, so we may come to the same node again.
To avoid processing a node more than once, we use a boolean visited array. 
For simplicity, it is assumed that all vertices are reachable from the starting vertex.

For example, in the following graph, we **_start traversal from vertex 2._**
When we come to vertex 0, we look for all adjacent vertices of it.
2 is also an adjacent vertex of 0. If we don’t mark visited vertices, 
then 2 will be processed again and it will become a non-terminating process. 
A Breadth First Traversal of the following graph is 2, 0, 3, 1.

![image](https://user-images.githubusercontent.com/51750338/61994760-6c4ec880-b09c-11e9-8d59-f4c9dba7d509.png)


