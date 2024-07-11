One-week group project (five person mob programming) during first year education.

---------------------------------------------------------------------------------------------------------------------------


Reworking a php assignment with C#.

We added the IHttpContextAccessor, to be able to use the Cookies for storing our "cart object".
https://stackoverflow.com/questions/38184583/how-to-add-ihttpcontextaccessor-in-the-startup-class-in-the-di-in-asp-net-core-1

How to Turn a C# Object Into a JSON String in .NET? .
https://code-maze.com/csharp-object-into-json-string-dotnet/

Initializing the Cart cookie, as soon as someone enters the webpage, in the Homecontroller, Index method
Then adding a serialize and deserilize method in CartsController so we can add and remove from the cart.

We found a solution, or we, rather one person in our group spent sometime and worked our problem with the connections and that we had to reset them everytime but now its working as intended.

Most basic finctionality is in place, still some refactoring, cleanup, styling etc.

We didn't put anytime into the authorization and logins, but used the auto complete for that.
The only thing we've implemented into the project that needs to be logged in is a create button that is only showing if we are logged in. 

We would have liked to look more into how to set roles etc and giving them different levels of access...