# Enter LINQ

* LINQ is a technology that gives you the ability to query data from the C# language.
* By data, I mean you can query objects that are in-memory on the heap, objects you've persisted into a database, objects behind web services, objects in XML, object anywhere there's a LINQ provider.
* LINQ provides over 50 query operators you can use (sorting, joining, filtering, projection, grouping, aggregation, partitioning, etc.)
* LINQ operators are definied as methods.
* Before LINQ was a type (like an interface), but that caused issues. Ultimately, Microsoft decided not to define a new type to hold all these LINQ operators. It's not flexible, scalable, doesn't support change over time. 
