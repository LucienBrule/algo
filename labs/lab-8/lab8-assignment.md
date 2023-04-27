# Lab 8
> Spanning Trees

In this lab you will implement a special type of spanning tree in which a subset of the vertices
must be leaf node.

The output spanning tree may not be a MST. So here is the problem:

Input: undirected graph G=(V,E); edge weights w(e), and a subset U of the of the vertices.

Output: a spanning tree that has nodes in U as leaf nodes and the total weight of the node is minimum.

Can you find an algorithm that runs in time O(|E| log |V|) time? Why? Or why not?

Test your code on the following instance of the problem G=(V,E)

V= {A,B,C,D,E,F,G,H,I}

E={(A-B,10), (A-C,12), (B-C,9), (B-D,8), (C-E,3), (C-F,1), (D-E,7), (D-G,8), (D-H,5), (E-F, 3) (F-H,6), (G,H,9), (G-I,2), (H-I,11)} where A-B is a link with weight 10.

U={A, D, F}.
