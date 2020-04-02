### Week 3, Friday
## Trees
Binary Trees and Binary search trees are data structures similar to our class hierarchy that we dealt with while learning inheritance. They have nodes, but the nodes are connected *parent* to *children*, instead of in a list or stack or queue. the children branch off on different *edges*, all based from the *root* parent, and then their children branch off further, growing possibly exponentially.  

Traversing binary trees can be done either by breadth or by depth. Traversing by depth prioritizes reading through each branch of the tree fully, from *root* to *leaf*, before moving on to the next branch. This can be done in different orders of course; Pre-order, which prioritizes root first, in-order, which prioritizes left most branch through root to right, and post order, which prioritizes left-most leaf first, then right, and ends with the root.  
Traversing by breadth is a bit simpler in a way. by breadth always goes level by level, from the root, left to right.  
Depth traversal and breadth traversal are handled using two data structures we are already familiar with. while depth traversal is best performed with a stack model, breadth is much more suited to a queue model.  


#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)