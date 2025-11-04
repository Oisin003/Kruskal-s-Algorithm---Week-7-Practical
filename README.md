Kruskal-s-Algorithm---Week-7-Practical
Oisin Gibson - L00172671 

Reference: https://www.geeksforgeeks.org/dsa/kruskals-minimum-spanning-tree-algorithm-greedy-algo-2/

Notes:
Kruskal's Greedy Algorithm for finding minimum spanning trees
Automatically creates edges between all number pairs
Edge weights calculated as absolute differences
Efficient cycle detection using DSU
Sorts edges by weight for optimal selection
Displays actual number connections 

Taken from Geeks for Geeks:
Sort all the edges in a non-decreasing order of their weight. 
Pick the smallest edge. Check if it forms a cycle with the spanning tree formed so far. If the cycle is not formed, include this edge. Else, discard it. 
Repeat step 2 until there are (V-1) edges in the spanning tree.
