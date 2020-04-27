### Week 7, Monday
## View Components
View components are essentially a more powerful version of view partials, like we learned to use in 301. They are not views, and cannot us model binding like a view, they instead use whatever parameters are passed into the calling method.  
View components contain a "view" and a class, just like regular razor pages, but are created either by deriving the class directly from the `ViewCompontent` base class, or by using the `[ViewComponent]` attribute to decorate the class, and they should contain "ViewComponent" as their class suffix.  
A view component will implement an `InvokeAsync()` method, with whatever parameters are needed, and that method is what you will use in your razor page syntax to attach the component. Notice that this is an "async" method, and will need to be awaited on pageload. 

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)