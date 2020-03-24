### Week 2, Tuesday
## Collections

__Summary__
Interfaces are similar to abstract base classes, except for a few things. Most important, any class can implement as many interfaces as they want, but can only derive from a single base class. Also, interfaces cannot contain abstract members. Since an interface cannot be instatiated directly, all of its members must first be implemented in the class that is using it. 
In our Back to Basics reading, it is suggested that one should only create and implement an interface if the members of it are going to be implemented in more than one class. This makes sense, as why wouldn't we just include those members directly in the class definition if we weren't going to implement them differently elsewhere? That's the whole reasoning behind the abstract keyword.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)