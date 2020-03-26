### Week 2, Thursday
## LINQ

#### Language-Integrated Query  
Language-Integrated Query (LINQ) integrates query methodologies directly with C#. Unlike in javascript, where we had to communicate between our script files and our SQL files to query our JSON or SQL database, in C#, the query language is built in. It should feel familiar too, it is based on SQL syntax, although I personally find LINQ's order of keywords much more intuitive, and human-readable. After learning about IEnumerables yesterday, Queries should come fairly quickly, as they have basically the same method structure. A query IS an IEnumerable object, used to set up and enumerate through a data base, sorting, grouping or selecting based on your specifications once you call foreach on it.

In LINQ there are a few familiar keywords similar to SQL:  
`from potato in Potatoes` > the *from* keyword is used to clarify your database that you are querying. Although queries should be strongly-typed, like everything in C#, the query can infer *potato*'s type from the database.

`where potato.Color == "green"` > where is our filtering keyword, and can be followed with any boolean C# logic you like (I think love LINQ, guys)

`orderby potato.Id descending` > you can also use the orderby keyword, just like in SQL to order your results by any alphanumeric value. strings will order A-Z, and numeric types will order, well, numerically...

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)
