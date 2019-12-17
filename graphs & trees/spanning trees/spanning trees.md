# Spanning Tree

Spanning tree of an undirected graph is a subgraph that includes all vertices and minimum possible number of edges.

Tree - Undirected graph with no cycles.
Fundamental Cycle - Adding just one edge to the spanning tree will create a cycle.  
Fundamental Cutset - Removing just one edge to the spanning tree will create disjoint sets.
Spanning Forest - In unconnected graphs disjoint set of spanning trees is referred as spanning forest.

# Properties
Possible multiplicity - In a `n` vertices graph, the spanning tree will have `n-1` edges.
Uniqueness - If the weights on the edges are unique, then there can be only one MST

# Minimum Spanning Tree/Minimum Weight Spanning Tree
Spanning tree whose sum of edge weights are as small as possible


https://en.wikipedia.org/wiki/Minimum_spanning_tree

# Spanning trees in Directed Graphs
The equivalent of MST in directed graph is optimum branching or minimum-cost arborescence. The classical algorithm is (Edmonds')[https://en.wikipedia.org/wiki/Edmonds%27_algorithm]
