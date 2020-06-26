# Trees
A tree is a nonlinear data structure, compared to arrays, linked lists, stacks and queues which are linear data structures. A tree can be empty with no nodes or a tree is a structure consisting of one node called the root and zero or one or more subtrees.</br>
**Conditions to be a tree**</br>

    Must be connected
    Must not be a cycle. If its cycle then its not a tree
*First element is called as Root*</br>

    Node : Individual element in a tree
    Nodes are described with Parent Child Relationship
    Parent : The node at a lower level is called Parent
    Child : The node connected to a higher level is called Child
    A node in the middle can be a parent or child depends on what it is connected to.
</br>

    Internal Node: Parent node is also called as Internal Node
    Height of a Node : Number of edges between it and the furthest leaf on the tree

*Leaf has height ZERO*</br>


    Height of the tree : It is just height of the Root Node
    Depth of the node : Number of edges to the root

    Height and Depth are inversely proportional in relation

**Each Node can only have 1 parent but a parent can have any number of children**</br>
**Exception : Root node has no parent**
## Tree Traversal
Trees aren't linear so how to traverse????</br>
Should we traverse left or right first ?</br>
Should we traverse one subtree or  one section of the tree including parent?</br>
Should we traverse all its descendants or traverse everything at same level first???
**Confused No need to worry. There are so many ways to traverse**</br>

    DFS(Depth First Search) - Where children nodes are priority
    BFS(Breadth First Search) - Visiting everything on same level. Its also called as Level Order Tree

## Depth First Search
Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.</br>

## Breadth First Search
Breadth First Search starts at the root and it visits it children on second level then their children untill we visit every leaf</br>
So its called as Level Order Tree</br>
We start at the left side most time</br>
From Example below BFS is D,B,E,A,C,F 

Example </br>

                        D
                B               E
            A       C               F

### Types of Traversal in DFS
1) Pre-Order Traversal</br>

    First we will visit  root next one of the children on
    the left most node untill we complete all level, Once
    sub tree is done then right side to it
    From Example
    Pre-order Traversal is D,B,A,C,E,F
2) In-Order Traversal</br>

    First left sub tree is visited then the Root and then
    the right sub tree
    From Example
    In-Order Traversal is A,B,C,D,E,F
3) Post-Order Traversal</br>

    Process all nodes of a tree by recursively processing
    all subtrees, then finally processing the root
    From Example
    Post-Order Traversal is A,C,B,F,E,D

## Binary Trees
Parents have atmost Two Children</br>
From Example we need to search an element in the tree and we have to go through each and every element</br>
So it is Linear Search and O(n) is efficiency</br>
## Binary Search Tree

    BSTs (Binary Search Tree) are sorted so every value on
    the left of a particular node is smaller than it and
    every value on the right of a pariticular node is larger
    than it.
    We can easily perforn search, delete and insert options
    very easily
    Searching is height of the tree so its efficiency is 
    log(n)
    BST Complication : unbalanced tree is the worst case scenario of the BST