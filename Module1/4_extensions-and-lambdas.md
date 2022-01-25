# Extensions and Lambdas

* Under the hood, now we know that all the LINQ operators are defined as extension methods in the `System.Linq` namespace.
* How do you pass code around for these LINQ operators to work?:
    * `=>` goes to/lambda expressions operator. Under the hood, delegates are involved, but LINQ encapsulates/hides this code.
    * The left hand side of the expression expresses the signature of the method. And on the right, the body of that delegate is to execute/return the right side of the expression. 