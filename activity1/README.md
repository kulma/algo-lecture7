# Activities

## Task 1:

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Graph/GraphIntroSumm.html

> You can refer to [link #2](#links) below for more info.

> Two vertices of a graph are ADJACENT if there is an edge joining them. - TRUE
> A graph without cycles is called a/an: - Acyclic graph
> A complete graph is a clique of size: IVI
> A DAG is a directed graph without cycles. - TRUE
> Two vertices of a graph are ADJACENT if there is an edge joining them. - TRUE


## Task 2

- Discuss how depth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/DFSAV.html

> You can refer to [link #3](#links) below for more info.
> A node is selected as a starting point and marked. Then, DFS goes to an adjacent node, marking it and pushing the first node into the recursion stack. From the new node, it goes into another still unmarked node, until it can't get any further. Then, it pops a node from the recursion stack and backtracks to see if it can get to any unmarked nodes from that, all the way to the first node. Undirected and directed work the same way, but with directed graphs the edges are unidirectional, which affects the traversal accordingly.

## Task 3

- Discuss how breadth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSAV.html

> You can refer to [link #4](#links) below for more info.
> With BFS, instead of going from a node to the next adjacent unmarked node to another unmarked node adjacent to that, it marks and queues all adjacent nodes (to the original node) before moving to the next node in the queue (in alphabetical order). It then again marks and queues all unmarked adjacent nodes, and so on, until all possible nodes are marked and the queue is emptied. Again, with directed graphs, the unidirectional edges affect the traversal accordingly.

## Task 4:

- Reproduce the behavior of the BFS algorithm for the following graph:
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSPE.html

> You can refer to [link #4](#links) below.

## Task 5: Individual (at home)

- There are two traditional approaches to representing graphs: The adjacency matrix and the adjacency list. What are the main differences in term of space/time complexity. You can refer to following link:
  https://www.baeldung.com/cs/adjacency-matrix-list-complexity

> Both of them are methods to represent a graph in computer's memory. 
> If the adjacency matrix graph has n vertices, the time complexity of the matrix is O(n^2) and the space complexity is also O(n^2)
> The adjacency list where m is the number of edges in a graph, then the time complexity of the list is O(m). The space complexity is O(n + m). But, in the worst case of a complete graph, which contains n \ 2 edges, the time and space complexities reduce to O(n^2)

## Links

1. https://cpp.sh/
2. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphIntro.html
3. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#depth-first-search
4. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#breadth-first-search
