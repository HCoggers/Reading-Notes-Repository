### Week 6, Tuesday
## Razor Pages

Razor Pages may look similar to Razor Views at first gglance, but the `@page` directive at the top of every Razor page makes them behave like an action. This means that they don't need to go through a controller, unlike with our previous views.

To bring a PageModel class into a razor page, like we brought models into our views, a class must be set up with the same name as the page, followed by the `.cs` file extension. 

Most of the logic that would originally be handled in a controller can be transferred to the page model class as handler methods, such as the `OnPostAsync` method. This method, in razor pages, will call a `RedirectToPage` helper, similar to how we would `RedirectToAction`, but customized for pages.

Remember to put all of your pages in a `Pages` folder, not your views folder, even your layouts. Razor pages rely on folder hierarchy, so any page in the pages ffolder will have access to any other page, but will likely not go looking under the conventional `/views`.



#### [Table of Contents](https://hcoggers.github.io/Reading-Notes-Repository/)