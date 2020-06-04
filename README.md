# Computational Thinking Modelling with Graphs Coursework

## Part A

### Task 1

Create a file `greedy_col_basic.py` such that when you run this file:

- It visits the vertices of the input graph sequentially in the order 1,2,3...
- At every step it assigns (in a greedy fashion) to the currently visited node the smallest possible colour such that no two adjacent nodes receive the same colour
- It outputs the constructed colouring and the number `kmax` of the different colours in this colouring.

### Task 2

Create a file `greedy_col_variation.py` such that when you run this file:

- It visits the vertices of the input graph in such an order that always the next visited node is adjacent to at least one previously visited node
- Among all such vertices, the algorithm visits at every step the smallest one
- At every step it assigns (in a greedy fashion) to the currently visited vertex the smallest possible colour such that no two adjacent nodes receive the same colour
- It outputs the constructed colouring and the number `kmax` of the distinct colours in this colouring.

## Part B

### Task 1

Create a file `breadth_first.py` with a function `bfs(G,a,b)` such that when you run this file:

- It performs a Breadth-First-Search starting from node `a` and ending it when it reaches node `b`
- It outputs the distance between the given pairs of nodes for the 5 input graphs

### Task 2

Create a file `breadth_first_pair_nodes.py` with a function `dfs(G,a,b,u)` such that when you run this file:

- It performs a Depth-First Search starting from a node `a` and ending when it reaches node `b`
- At every step, among the neighbours of the currently visited vertex, the algorithm chooses the smallest one to continue the exploration from it
- In addition, it adds a label to each of the visited nodes, such that if a vertex `v` receives the label `i`, then this Depth-First-Search has reached a vertex `v` with a path of length `i`(starting from `a`)

### Task 3

Create a file `diameter.py` such that when you run this file

- It outputs the greatest distance between any pair of vertices in the input graph
