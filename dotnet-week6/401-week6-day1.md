### Week 6, Monday
## MVC Core Identity Quiz

1. What does calling the method `App.UseAuthentication()` do in our startup file?
2. What does calling the method `services.AddDefaultIdentity<TUser>()` do?
2. What effect does the `[Authorize]` attribute have when applied to a web page?
3. What is the difference between Authorization and Authentication?
4. What does the term "OAuth" refer to?

> 1. `App.UseAuthentication()` Adds the AuthenticationMiddleware to the specified IApplicationBuilder, which enables authentication capabilities.
> 2. Adds a set of common identity services to the application, including a default UI, token providers, and configures authentication to use identity cookies.
> 2. `[Authorize]` Specifies that the class or method that this attribute is applied to requires the specified authorization.
> 3. **Authentication** is the process of determining a user's identity. **Authorization** is the process of determining whether a user has access to a resource.
> 4. **OAuth** is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)