### Week 7, Wednesday
## OAUTH
OAuth is the practice of using external authentication services to register or log users in, such as Facebook, Google, Github, etc. In order to do this, just like with API keys, we need to get some information from the provider, and store it in our user secrets. For OAuth, we need to register our specific application with the service provider, and in exchange we will get a client id and a client secret that will be used to authenticate the user.  
 Once you have stored the client ID and client secret in user secrets, you will want to register the oauth and server authentication services in your startup file, in the `Services.AddAuthentication` method call, using your new user secrets.  
 Remember that this works much like an API call, so when you make your authentication request to OAuth, you're going to recieve a lot of user information as a JSON object, and you will need to serialize and sort through it to find the proper authentication properties you're looking for.

#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)