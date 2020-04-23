### Week 6, Thursday
## Policies
Policies, in claims-based authorization are how we test the principal's claims to determine what authorizations they have. For instance, you could have a policy that someone must be over the age of 21 to view a page on a site, so you would read their birthdate claim to determine if they are old enough. These policies are registered in our authorization service in the setup file.  
Authorize attributes can be used on razor pages and controllers to specify a specific required authorization to return the page.  
Authorization policies need a requirement to compare against a provided claim. A requirement can have a single parameter, or a collection of parameters, but all parameters must be met in order for the requirement to be met. This means that if you want to have multiple outcomes for a specific claim or set of claims, you need to devvelop multiple requirements. You cannot include them all in one.  
The requirement should implement the IAuthorizationRequirement interface as a marker to declare whether or not the requirement has been met.  
This makes deciding what claims should be collected especially important, since you can't make a policy on a claim that a user doesn't have. You can't check if someone's email is provided by a trusted email servicce if you never create an email claim for that principal.  

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)