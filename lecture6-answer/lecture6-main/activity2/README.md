# Activities

## Task 1

- Refer to the following link. Discuss how Binary Search Trees work:
  https://www.cs.usfca.edu/~galles/visualization/BST.html

## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-binary-search-tree/

Discuss the Time and Space complexity of Binary Search Tree (BST) operations (Searching, Insertion, Deletion) in the Best case, average case and worst case.



    Time complexity:

    i. Best case: When we get the root node as the node which is supposed to be searched then in that case we have to make onle one comparison so time taken would be constant. Time complexity in best case would be O(1).

    ii. Average case: When there is a balanced binary search tree(a binary search tree is called balanced if height difference of nodes on left and right subtree is not more than one), so height becomes logN where N is number of nodes in a tree.
    In search operation we will keep on traversing through nodes one by one, suppose if we find the element in second level so for doing so we have done 2 comparisons, if we get element in third level we will be doing 3 comparisons so in this way we can say that the time taken to search for a key in binary search tree is same as the height of the tree which is logN, so time complexity for searching is O(logN) in average case.
   Average Height of a Binary Search Tree is 4.31107 ln(N) - 1.9531 lnln(N) + O(1) that is O(logN).

   iii. Worst case: If the tree is unbalanced or if it is skewed binary search tree(skewed binary search tree is a tree in which there are no nodes available in left subtree or right subtree see the image below to get better understanding)
   In this case we have to traverse from root to the deepest leaf node and in that case height of the tree becomes n and as we have seen above time taken is same as the height of the tree so time complexity in worst case becomes O(n).


Space complexity: The space complexity of searching a node in a BST would be O(n) with 'n' being the depth of the tree(number of nodes present in a tree) since at any point of time maximum number of stack frames that could be present in memory is 'n'.
## Task 3

- Explain how the code in ./src/bst.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/introduction-to-binary-search-tree-data-structure-and-algorithm-tutorials/

## Task 4: Individual (at home)

- Refer to the following link. Explain how In-order Traversal is used to print a binary search tree.
  https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html#inorder-traversal

  An inorder traversal first visits the left child (including its entire subtree), then visits the node, and finally visits the right child (including its entire subtree). The binary search tree makes use of this traversal to print all nodes in ascending order of value.



## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/binary-search-tree-data-structure/
