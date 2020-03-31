### Week 3, Tueday
## Intro to ERDS  
---  
### Schemas
- Database Schema is a term used to describe a representation, or visual blueprint, of a dataset. 
- We can use them either to plan out a new database (similar to our zoo app whiteboarding), or to demostrate the structure of an existing database to a newcomer or client.
- An organized database schema will look a bit like family tree, with sections representing objects, including summaries of their behaviors and attributes within.

### Database Keys
- Primary keys are unique value types that are going to be different for every data entry in a database. They should be such that they are never, or rarely altered over the lifespan of the database.
- A Foreign Key is similar to a primary key, except that it alludes to a data entry in a different dataset than the one you are working in. this can be useful when combining or comparing databases.
- A Composite key is built from two different properties of a data entry, to uniquely identify that entry, just like a primary key would. For instance, a composite key could be made of a latitude and longitude value, even if another location had the same longitude value. Or the same latitude. but not both. Unique, see?

### Relational Databases
- 1:1 relationships define relationships between two tables where a foreign key in one corresponds to a single primary key in another. consistently matching one data entry to one other data entry.
- Many:Many relationships are when you have two datasets, and a third, linking dataset, that has foreign keys to both sets, connecting them indirectly.
- 1:Many is when a dataset has foreign key that corresponds to a nonunique key in another set, creating a connection between one entry on one side to many on the other.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)