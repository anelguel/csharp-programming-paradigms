# Funcs and Expressions

* When you're working with LINQ against a remote datasource, where the data is not in-momory, a LINQ provider will translate your LINQ queries/method invocations (like `where`, `orderby`, etc). It will translate them into an efficient command for the datasource. 
* Does LINQ have to decompile what you've written in C# code, because all of this happens at runtime. Does it decompile the Microsoft Intermediate Language Instructions or the IL that the C# compiler produces? Answer: NO. 
    * A LINQ provider doesn't decompile your code, instead it has some help from the compiler in understanding the LINQ query you've written, thanks to the expression type. Expressions wrap a `Func<T>` type and they are in collusion with the C# compiler.

* How do our expressions get translated to expressions in SQL Server?
    * All of the remote LINQ providers implement properties that are `IQueryable` to allow you to get to information that's on that remote data source.
    * The LINQ providers don't work with `Funcs` that compile down to delegates, instead they take the `Funcs` and wrap them with `Expression<T>`. And when the C# compiler sees an `Expression<t>` it no longer compiles this lambda expression into IL. Instead it builds a data structure, or Abstract Syntax Trees that has objects inside that represent the operations that we have expressed in code.
        * I.e., it gets translated to a data structure that entity framework uses to translate between .NET and SQL Server?