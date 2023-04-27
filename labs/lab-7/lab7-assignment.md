# Lab 7

> Dijkstra's Algorithm,

In this lab we will implement dijkstra's shortest path algorithm as described in Fig 4.8.
Dijkstra's algorithm is a n efficient method for finding the shortest path between two nodes in a weighted graph.
It can be used in various applications, such as navigation systems, network routing and transportation planing.

We will use the HeapDict priority queue implementation to manage the nodes during execution of the algorithm.
This datastructure works like a dictionary, allowing both insert and decrease key operations by simply setting the dictionary key to a given value.
It also supports the delete min operation via popitem.

The input graph will be specified as a pair of edges and weights; the example graph shown in Fig 4.9 is available as:

| u   | v   | w   |
|-----|-----|-----|
| 1   | 2   | 4   |
| 1   | 4   | 2   |
| 2   | 3   | 2   |
| 2   | 4   | 3   |
| 2   | 5   | 3   |
| 4   | 2   | 1   |
| 4   | 3   | 4   |
| 4   | 5   | 5   |
| 5   | 3   | 1   |


For example, the first line 1 2 4 means that the directed edge (1,2) has weight 4.

The output should be as shown in Fig 4.9 when called with 1 as the source node, as follows: 

1. 0, [ 1 ]
2. 3, [ 1,4,2 ]
3. 5, [ 1,4,2,3 ]
4. 2, [ 1,4 ]
5. 6, [ 1,4,2,5 ]

The format per line is vertex id: distance from vv, shortest path from vv

Test your code on the following dataset: rome99.txt (posted on Piazza). This graph contains a large portion of the directed road network of the city of Rome, Italy, from 1999. The graph contains 3353 vertices and 8870 edges.
