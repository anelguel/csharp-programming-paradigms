# Extension Methods

* `IEnumerable<T>`, the lowest data source for LINQ. This is the perfect interface for hiding the true source of data, because it defines only one method, `GetEnumerator()`.
    * `GetEnumerator()` returns an object that will let you step through data one at a time like you would do in a `foreach` loop.
* `IEnumerable<T>` is perfect for hiding the source of data, but it doesn't do so well defining interesting methods for querying data. You can only loop throught the data source.
    * Microsoft took the approach of adding *extension* methods to the language and extending `INumerable<T>`. An extension method is a method that looks like it's a member type of a given type, when in reality it's just a static method on a different type. It uses the `this` keyword.
    * In a nutshell, this is what LINQ does.
    * Call LINQ by bringing in `System.Linq`. 
