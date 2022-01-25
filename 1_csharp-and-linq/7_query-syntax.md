# Query Syntax

* The Comprehension Query Syntax (new syntax Microsoft introduced for queries) looks like structured query language, but it is in fact C# code. The C# compiler will compile this into IL.
    * Under the hood, the C# compiler transforms the comprehension query syntax into a series of extension method calls.