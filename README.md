An AVL tree is a self-balancing binary search tree named after its inventors, Adelson-Velsky and Landis. In an AVL tree, the heights of the two child subtrees of any node differ by at most one, ensuring O(log n) time complexity for search, insertion, and deletion operations. Here are some key features and operations of AVL trees:

Key Features
Balance Factor: For any node in the AVL tree, the balance factor is the difference in height between its left and right subtrees. It can be -1, 0, or +1. If any node's balance factor becomes less than -1 or greater than +1, the tree needs rebalancing.

Height Balance: An AVL tree maintains its height balance after every insertion and deletion operation to ensure logarithmic height.

Rotations
To maintain the balance of an AVL tree, rotations are used. There are four types of rotations:

Left Rotation (LL Rotation): Used when a node is inserted into the right subtree of the right child.
Right Rotation (RR Rotation): Used when a node is inserted into the left subtree of the left child.
Left-Right Rotation (LR Rotation): Used when a node is inserted into the right subtree of the left child.
Right-Left Rotation (RL Rotation): Used when a node is inserted into the left subtree of the right child.
Operations
Insertion: Similar to the insertion in a binary search tree, followed by checking and restoring balance using rotations if necessary.
Deletion: Similar to the deletion in a binary search tree, followed by checking and restoring balance using rotations if necessary.
Search: Follows the binary search tree search algorithm, ensuring O(log n) complexity due to the balanced nature of the AVL tree.
