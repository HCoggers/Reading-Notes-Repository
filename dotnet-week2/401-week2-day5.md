### Week 2, Friday
## Stacks & Queues

Stacks and queues, building on our work with linked lists last week, are both similarly linked lists but with very specific actions we can perform on them. 

Lets take a stack first, This should make since because it works the same way as our buddy the callstack, from back in javascript. a stack is a list of nodes, each with a single reference to the next node, and an assigned top node. any node added or removed from this stack will be assigned or de-assigned to that top reference. In this way, the stack uses First-In-Last-Out behavior, just like the call stack. Only the top node is ever interacted with. On a stack, we can perform a *Push* to add a node to the top, a *Pop* to remove the top node, a *Peek* to look at the top node without displacing it, and *IsEmpty*, which checks if there are any nodes in the stack, so as not to throw exceptions from our Pops and Peeks.

The queue is similar in structure, but opposite in behavior. The only structural difference is that a queue has an end reference and a start reference. In behavior, a queue is First-In, First-Out, just like a queue at the grocery store, the person at the start node will be removed, or *Dequeued*, and any new node will be *Enqueued* as the new end of the queue, and have to traverse the whole line again to be removed. This list can also be peeked or checked for IsEmpty, but the node you can peek is only the start, not the end node.



#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)