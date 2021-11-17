# Trees
- Binary Trees
- Binary Search Trees
- K-ary Trees

## Some Terminologies
- Root: The root is the node at the beginning of the tree.
- K: Number of childs (links out of the node)  
> In a binary tree, k = 2 max.
- Leaf - A leaf is a node that does not have any children
- Edge - The edge in a tree is the link between a parent and child node
- Height - The height of a tree is the number of edges from the root to the furthest leaf

## Depth First (stack)
we prioritize going through the depth (height) of the tree first. 

**methods**:
1. Pre-order: root >> left >> right
2. In-order: left >> root >> right
3. Post-order: left >> right >> root

## Breadth First (queue)
iterates through the tree by going through each level of the tree node-by-node.

## Binary Tree Vs K-ary Trees (queue also)
can have any number of children per node, but Binary Trees restrict the number of children to two.

## Binary Search Trees
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree.
If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.


