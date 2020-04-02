### Week 3, Thursday
## Entity Framework Core & Data Seeding
Data seeding is how we populate a database with dummy data to ensure everything is working properly. Entity Framework Core allows us to do this a variety of ways. We can seed data with an entity type. Alternatively, If we don't already have a database created, we can use the EnsureCreated() method to create a new database with seed data. EnsureCreated() will not update or seed data on an already created database, so it's not always going to be your go to.  
Manual migration customization is the use of the HasData method, which will convert to Insert, Update, or Delete methods, based on the changes specified. One can manually use any of those three data methods to clarify specifically the operations to be made.

Keep in mind, seeding data should not be part of normal app deployment, it should only be used in development, not "production"


#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)