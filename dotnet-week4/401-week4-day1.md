### Week 4, Monday
## SOLID Design Principles
The Solid Design principles are five principles to follow for writing simplified, streamlined, and *testable* code.

1. __Single Responsibility__  
    This is the one you've probably heard of, especially if you are conscious of Test-Driven-Development. The single responsibility principle just says that each method or class or interface in your code should only have a single reason to change. A single responsibilty it has to take on. If you find that by modifying, or updating one section of your code, you have to go back through and update other classes or methods to keep everything in line, you probably want to simplify how many things your doing in a single code block.
2. __Open-Closed__  
    A module should be *open for extension*, but *closed to modification*. That's the basic premise of the open-closed principle. Your modules should be dependable, but general enough that they don't need to be modified to exhibit a variety of behavior. At this point you're used to importing libraries written by other developers, you know how easily you can use those new methods and data types, without needing to edit them in any way. Your code should work just like that.
3. __~~Lumpy Space Princess~~ Liskov Substitution Principle__  
    Just like we learned from our OOP principle polymorphism, LSP says any instance of a class derived from another should be interchangeable anywhere where that base class is instantiated, without breaking the code. Any logic performed on an animal array should work just as well whether those animals are cats, dogs, or both.
4. __Interface Segregation__  
    Just like your single responsibility methods, your interfaces should be just as barebones. You should have many more very very specific interfaces for your client to use, rather than one overwhelming interface that takes hours to navigate through.
5. __Dependency Inversion__  
    Code Should depend on abstractions, not concretions. What does that mean? It means something very similar in spirit to our previous LSP. The more our code depends on hard-coded, instantiated objects, rather than types and abstractions, the less flexible it will be once actually in production and being used by clients. Details in the code should be based on the abstract classes you have built out, not the other way around.


#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)