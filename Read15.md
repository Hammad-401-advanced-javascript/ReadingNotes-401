# Trees

### There are two categories of traversals when it comes to trees:
* Depth First
* Breadth First

**The most common way to traverse through a tree is to use recursion. With these traversals, we rely on the call stack to navigate back up 
the tree when we have reached the end of a sub-path**

**Notice the similarities between the three different traversals above. The biggest difference between each of the traversals is when
you are looking at the root node.**

## Adding a node

**Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node
gets placed.**

**One strategy for adding a new node to a binary tree is to fill all “child” spots from the top down. To do so, we would leverage the 
use of breadth first traversal. During the traversal, we find the first node that does not have 2 child nodes, and insert the new
node as a child. We fill the child slots from left to right.**

**In the event you would like to have a node placed in a specific location, you need to reference both the new node to create,
and the parent node upon which the child is attached to.**

**Big O
The Big O time complexity for inserting a new node is O(n). Searching for a specific node will also be O(n). Because of the lack of
organizational structure in a Binary Tree, the worst case for most operations will involve traversing the entire tree. If we assume
that a tree has n nodes, then in the worst case we will have to look at n items, hence the O(n) complexity.**

**The Big O space complexity for a node insertion using breadth first insertion will be O(w), where w is the largest width of the tree.
For example, in the above tree, w is 4.**

**A “perfect” binary tree is one where every non-leaf node has exactly two children. The maximum width for a perfect binary tree, is
2^(h-1), where h is the height of the tree. Height can be calculated as log n, where n is the number of nodes.**

![image](https://media.geeksforgeeks.org/wp-content/cdn-uploads/TreeToList.png)
