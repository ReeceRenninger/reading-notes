# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Trees

### Tree Cheat Sheet for the Basics:

      Common Terminology:
      
    Node - A Tree node is a component which may contain its own values, and references to other nodes

    Root - The root is the node at the beginning of the tree

    K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.

    Left - A reference to one child node, in a binary tree

    Right - A reference to the other child node, in a binary tree

    Edge - The edge in a tree is the link between a parent and 
    child node

    Leaf - A leaf is a node that does not have any children

    Height - The height of a tree is the number of edges from the root to the furthest leaf

### Traversals:
      Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. Here are three methods for depth first traversal:

    Pre-order: root >> left >> right
    In-order: left >> root >> right
    Post-order: left >> right >> root

A good visual to represent the 3 methods mentioned above:

![3 methods of traversal in trees](../imgs/Screenshot%202023-05-25%20214907.png)

- Pre order code:
```javascript
ALGORITHM preOrder(root)

  OUTPUT <-- root.value

  if root.left is not NULL
      preOrder(root.left)

  if root.right is not NULL
      preOrder(root.right)

```
- In-order Code:
```javascript
ALGORITHM inOrder(root)
// INPUT <-- root node
// OUTPUT <-- in-order output of tree node's values

    if root.left is not NULL
        inOrder(root.left)

    OUTPUT <-- root.value

    if root.right is not NULL
        inOrder(root.right)

```
- Post-order code:
```javascript
ALGORITHM postOrder(root)
// INPUT <-- root node
// OUTPUT <-- post-order output of tree node's values

    if root.left is not NULL
        postOrder(root.left)

    if root.right is not NULL
        postOrder(root.right)

    OUTPUT <-- root.value

```

      Breadth First

      Breadth first traversal iterates through the tree by going through each level of the tree node-by-node. So, given our starting tree one more time:
![Alt text](../imgs/Screenshot%202023-05-25%20215239.png)

      K-ary Trees
      If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.
![Alt text](../imgs/Screenshot%202023-05-25%20215723.png)

    Binary Search Trees
    A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.
![Alt text](../imgs/Screenshot%202023-05-25%20215956.png)

    Big O
    The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height). In the worst case, we will have to search all the way down to a leaf, which will require searching through as many nodes as the tree is tall. In a balanced (or “perfect”) tree, the height of the tree is log(n). In an unbalanced tree, the worst case height of the tree is n.

    The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.
## Bookmark


[]()

## Class Notes

## Things I want to know more about
