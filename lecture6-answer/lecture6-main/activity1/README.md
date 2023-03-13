# Activities

## Task 1: Tree Definition

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/DefSumm.html

 (1) What is the minimum number of internal nodes in a binary tree with 8 nodes?
4

(2)What is the minimum number of nodes in a complete binary tree with height 3? 7

## Task 2

- Explain how the code in ./src/bt.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-tree-array-implementation/

## Task 3: Tree Traversal

Refer to te following links. Discuss the difference between the different ways binary trees can be traversed.

- [Pre-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPreorderPRO.html)

1.Pre-order traversal

    To traverse a non-empty binary tree by pre-order method, the following operations are performed recursively until all nodes are visited:

    i. Visit the root node.

    ii. Traverse the left sub-tree fully.

    iii. Traverse the right sub-tree.
    Consider the example beside. The pre-order traversal of the tree is 70, 42,27, 11, 40, 66, 86, 81, 91. 
    As we see, we traverse the root node first, then the left sub-tree, then move to right sub-tree.
    The keyword ‘pre’ here means that the root node is accessed the very first.
    It is also known as depth first traversal.
    The pre-order traversal is used to extract a prefix notation from an expression tree.


- [Post-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPostorderPRO.html)

Post-Order traversal.

    To traverse a non-empty binary tree by post-order method, the following operations are performed recursively until all nodes are visited:

    i. Traverse the left sub-tree.

    ii. Now, move to the right sub tree

    iii. Then, finally visit the root node.

    Consider the example above. The post-order traversal of the tree is 11, 27, 42, 32, 14, 74, 96, 87, 58
    As we see, we traverse the left sub-tree first, then the right sub-tree and finally we visit the root node.
    The keyword ‘post specifies that the root node is accessed after we visit the left and right sub-trees.
    They are used to extract post fix notation from an expression tree



- [In-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravInorderPRO.html)
In-order traversal

    To traverse a non-empty binary tree by in-order method, the following operations are performed recursively until all nodes are visited:

    i. Traverse the left sub-tree.

    ii. Now, visit the root node.

    iii. Then, finally traverse the right sub-tree.
    Consider the example above. The in-order traversal of the tree is 21, 21, 27, 40, 50, 62, 80, 83, 96
    As we see, we traverse the left sub-tree first, then we moved to the root node and finally the right sub tree.
    The keyword ‘in’ specifies that the root node is accessed between left and right node.
    In-order traversal is used to display the elements of a binary search tree.

## Task 4: Individual (at home)

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/TravSumm.html
- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/Treeprobs.html

  (1) What is the depth of this tree?
  Trees have height -- they do not have depth

  (2) Which statement is correct?
The tree is full but not complete
The tree is full and complete
The tree is complete but not full
The tree is neither full nor complete- This is correct.

  (3) How many internal nodes does this tree have? 
    5

  (4) How many nodes in the tree have at least one sibling?

  6

  (5) What is the height of this tree?
  3
## Links

- https://cpp.sh/
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTree.html
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html
