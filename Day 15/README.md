<h2>Euler circuit and Path</h2>

https://www.geeksforgeeks.org/problems/euler-circuit-and-path/1

An Eulerian Path is a path in graph that visits every edge exactly once and it starts and ends up at different indexes. An Eulerian Circuit is an Eulerian Path which starts and ends on the same vertex. Given an undirected acyclic graph with V nodes, and E edges, with adjacency list adj, return 2 if the graph contains an eulerian circuit, else if the graph contains an eulerian path, return 1, otherwise, return 0.

Your Task:
You don't need to read or print anything. Your task is to complete the function isEulerCircuilt() which takes number of vertices in the graph denoted as V and an adjacency list of graph denoted as adj and returns 2 if the graph contains an eulerian circuit, else if the graph contains an eulerian path, it returns 1, otherwise, it will return 0.

Expected Time Complexity: O(V+E) where E is the number of edges in graph.
Expected Space Complexity: O(V)

Constraints:
1 ≤ V, E ≤ 104
1 ≤ adj[i][j] ≤ V-1
