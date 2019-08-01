# B Tree Rules #

//Minimum is a positive integer which is used to determine how many minimum elements are held in a single node.

* Properties
   1. B-tree nodes have more than 2 children.
   2. B-tree node may contain more than 1 element.
   
* Rules
  1. The root can have as few as 1 element; or even no elements if it has no children, every other node has at least minimum elements. 
  
  
  2. The maximum number of elements in a node is twice the value of MINIMUM.
  3. The elements of each B-tree node are stored in a partially filled array, sorted from the smallest element at index zero to the largest      element at the final position of the array.
  4. The number of subtrees below a nonleaf node is always one more than the number of elements in the node.
  5. For any nonleaf node, an element at index i is greater than all the elements in subtree number i of the node, also an element at index i is less than all the elements in a subtree number i+1 of the node
  6. Every leaf in a B-tree has the same depth thus it ensures that a B-tree avoids the problem of an unbalanced tree.
