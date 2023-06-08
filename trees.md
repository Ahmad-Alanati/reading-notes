# trees

## Common terminologys for a trees are:
1. Node: tree node has two element one of them is a value and the other is a references to the other nodes.
2. Root: the root is the node at the beginning of the tree.
3. k: the number of childern for any node.
4. Left: a reference to the one child node
5. Right: a reference to the other child node.
6. Edge: The edge in a tree is the link between a parent and child node
7. Leaf: A leaf is a node that does not have any children
8. Height: The height of a tree is the number of edges from the root to the furthest leaf

trees Traversals:

1. Depth First.
2. Breadth First.

### depth first

#### there are 3 way you can traverse the tree in depth first and here they are:

1. pre-order: root>>left>>right
2. in-order: left>>root>>right
3. post-order: left>>right>>root

ex:
![tree](./images/tree-example.png)

pre-order: A,B,D,E,C,F

in-order: D,B,E,A,F,C

post-order: D,E,B,F,C,A


### Breadth First

#### using the breadth first in traversing: 

ex:
![tree](./images/tree-example.png)

output: A, B, C, D, E, F

