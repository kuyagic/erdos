Title: Nodes and edges
Category: Graphs
Date: 2016-06-26
Position: 1
Summary: Graphs are made of nodes and edges

**Graph** is the mathematical term for a network, and we use these two terms
interchangeably throughout the problem sets.

A graph is defined as a set of **nodes**, defining the locations, sites or
elements of the graph, and a set of **edges**, representing the relationships
between two nodes.

![Alt text]({filename}/images/nodes_edges_example.png "A graph with four
 nodes and four edges.")

There are many ways to represent a graph, and both nodes and edges can have
many different properties. For now, we choose the simplest possible way to
represent a graph, where each node is represented by a single integer, and
each edge, by a pair of two nodes.

With these conventions, we could save a graph to a file by defining the
number of nodes, edges, and each edge in a separate line.

For this problem, you need to read a file in this format and find the node
with the most edges.

Note: for a given node `u`, the number of edges connecting to `u` is called
*degree* of u. If two nodes `u` and `v` are connected by an edge, they are
called *adjacent*, or *neighbors*.

### Input

The input is a file in the aforementioned format, where the first line
contains two integers, `n` and `m`, defining the number of nodes and edges,
respectively. The next `m` lines each contain two integers, reprsenting two
nodes that are joined by an edge.

### Output

Output the node with the highest degree.

### Test Input

```
4 4
0 1
0 2
1 3
3 0

```

### Test Output

```
0
```

--------------------------------------------------------
[Solution](https://github.com/Leockard/erdos/blob/master/solutions/graphs/nodes_edges.py).