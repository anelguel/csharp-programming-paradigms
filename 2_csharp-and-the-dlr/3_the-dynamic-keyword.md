# The Dynamic Keyword

* Static type checking does restrict the way you write some code. You have to have type definitions and metadata available at compile time to get any work done.
* C# introduced the `dynamic` keyword, it will statically type a variable as a dynamic variable. When the C# compiler sees a dynamically typed variable it turns off all compile type checks. Any operations you perform on a dynamic object, referenced by that variable, like calling a method or setting a property, they will all be resolved at runtime.