### Week 4, Wednesday
## Deployment And Unit Testing
__User Secrets__ are where we store any vital information that should not be distributed to a user or a client. User Secrets stay on our local machine, outside of our repo.  
A user secrets file, just like our *appsettings* file, which it will be replacing, is formatted in JSON key-value pairs. Our codebase will reference the keyvalue, and use a specific UserSecrets Id which will populate in our csproj file, to find the corresponding value in our UserSecrets.  
In order to implement user secrets, right-click on your project in visual studio, and select manage user secrets. It will open up a secrets.json file where all your K-V pairs can go. You can edit and save this file at any time. Now we have to tell our project how to use it.  
Go to your startup file, and edit its constructor to this: 
```
public IConfiguration Configuration { get; }

public Startup(IConfiguration configuration)
{
    var builder = new ConfigurationBuilder().AddEnvironmentVariables();
    builder.AddUserSecrets<Startup>();
    Configuration = builder.Build();
} 
```
This will build our configuration to accomodate the changes(notice our new AddUserSecrets() method).  
Remember, once a project is deployed, it won't have access to your local user secrets, so those will need to be transfered to azure's special handling of user secrets.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)