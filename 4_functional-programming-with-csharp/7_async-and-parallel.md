# Async and Parallel

* Task Parallel Library (TPL). Executes functions in parallel, so once you understand how to pass functions around as data, the library becomes very simple to use.
* `AsParallel()` LINQ operator, introduced in .NET 4.0, and what it will do is split the work inside of the query into multiple threads.
* `Parallel.Invoke` is another example, a couple other mentioned in the module. 

* The task Parallel library is another great example of a functional API that allows you to treat functions as data, to pass functions around, to have them executed in parallel or asynchronously, an to wait for them to complete.