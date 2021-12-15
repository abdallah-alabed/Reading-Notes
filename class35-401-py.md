# Graphs
A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

![graph](https://media.geeksforgeeks.org/wp-content/cdn-uploads/undirectedgraph.png)

## Directed vs Undirected:
|Directed|Undirected|
|-----|-----|
|Digraph is a graph where every edge is directed.Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.| each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.|

## Graph Types:
1. Complete: is when all nodes are connected to all other nodes.
2. Connected: A connected graph is graph that has all of vertices/nodes have at least one edge.
3. Disconnected: A disconnected graph is a graph where some vertices may not have edges.

![cVcVd](https://slidetodoc.com/presentation_image_h/30e712d7224bf2f20b37a065943b5b4c/image-4.jpg)

## Acyclic vs Cyclic:
|Acyclic|Cyclic|
|-----|-----|
|An acyclic graph is a directed graph without cycles.| A Cyclic graph is a graph that has cycles.|

## Graph Representation
1. Adjacency Matrix :  n x n Boolean matrix
2. Adjacency List : An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

## Weight Matrix
Adjacency Matrix multiplied with the edge weight.

## Real World Uses of Graphs

- GPS and Mapping
- Driving Directions
- Social Networks
- Airline Traffic
- Netflix uses graphs for suggestions of products


