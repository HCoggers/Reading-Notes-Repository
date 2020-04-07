### Week 4, Tuesday
## Views and Azure Deployment
Layouts and partials both do one thing very well for us. They reduce code duplication.  
*Layouts*, like our CSS stylesheets, allow us to keep a uniform "layout" throughout our webapp. by using the same or related layouts on every view, our users have a more concrete idea of how to use our app, and the transitions from view to view are smooth and responsive.   
*Partials* provide much the same functionality. Where as a layout is defining a setup for each entire view, partials are an individual module that can be imported into that view, or many different views, without repition. In 301, our main use for partials was to separate out our html heads, headers, and footers, as they were usually the same for every view. Through partial tag helpers, partials in dotNET are even more flexible and easy to implement, and combined with a proper layout file, our html might actually be legible for once!

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)