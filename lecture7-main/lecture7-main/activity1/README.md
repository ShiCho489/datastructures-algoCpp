# Activities

## Task 1:

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Graph/GraphIntroSumm.html

(1) A free tree is: a connected graph with no cycles.
(2) A weighted graph must have edge weights and be directed: False.
(3) Two vertices of a graph are ADJACENT if there is an edge joining them. True
(4) A complete graph is a clique of size: |V|
(5) Given a subset S of the vertices in a graph, when all vertices in S connect to all other vertices in S, this is called a: clique.

> You can refer to [link #2](#links) below for more info.

## Task 2

- Discuss how depth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/DFSAV.html

  DFS starts with a root node or a start node and then explores the adjacent nodes of the current node by going deeper into the graph or a tree. This means that in DFS the nodes are explored depth-wise until a node with no children is encountered.
  Once the leaf node is reached, DFS backtracks and starts exploring some more nodes in a similar fashion.
  In DFS we use a stack data structure for storing the nodes being explored. The edges that lead us to unexplored nodes are called ‘discovery edges’ while the edges leading to already visited nodes are called ‘block edges’.
  It works on recursive functions. 
  

> You can refer to [link #3](#links) below for more info.

## Task 3

- Discuss how breadth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSAV.html

  In the breadth-first traversal technique, the graph or tree is traversed breadth-wise. This technique uses the queue data structure to store the vertices or nodes and also to determine which vertex/node should be taken up next.

  Breadth-first algorithm starts with the root node and then traverses all the adjacent nodes. Then, it selects the nearest node and explores all the other unvisited nodes. This process is repeated until all the nodes in the graph are explored.

  It works on iterative approach.

> You can refer to [link #4](#links) below for more info.

## Task 4:

- Reproduce the behavior of the BFS algorithm for the following graph:
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSPE.html

> You can refer to [link #4](#links) below.

## Task 5: Individual (at home)

- There are two traditional approaches to representing graphs: The adjacency matrix and the adjacency list. What are the main differences in term of space/time complexity. You can refer to following link:

Adjacency Matrix:-The first way to represent a graph in a computer’s memory is to build an adjacency matrix. Assume our graph consists of n vertices numbered from 1 to n.  An adjacency matrix is a binary matrix of size n \times n. There are two possible values in each cell of the matrix: 0 and 1. Suppose there exists an edge between vertices v_{i} and v_{j}. It means, that the value in the i^{th} row and j^{th} column of such matrix is equal to 1. Importantly, if the graph is undirected then the matrix is symmetric.
Assuming the graph has {n} vertices, the time complexity to build such a matrix is {O(n^2)}. The space complexity is also {O(n^2)}.

Adjacency List:-The other way to represent a graph in memory is by building the adjacent list. If the graph consists of n vertices, then the list L contains n elements. Each element L_{i} is also a list and contains all the vertices, adjacent to the current vertex v_{i}. By choosing an adjacency list as a way to store the graph in memory, this may save us space.
If {m} is the number of edges in a graph, then the time complexity of building such a list is {O(m)}. The space complexity is {O(n + m)}. But, in the worst case of a complete graph, which contains {n \choose 2} edges, the time and space complexities reduce to O(n^2).
  https://www.baeldung.com/cs/adjacency-matrix-list-complexity

## Links

1. https://cpp.sh/
2. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphIntro.html
3. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#depth-first-search
4. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#breadth-first-search
