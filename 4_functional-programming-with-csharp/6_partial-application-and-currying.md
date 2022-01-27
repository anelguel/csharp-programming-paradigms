# Partial Application and Currying

* What happens if we need to retry a function that itself needs a parameter value?
* Partial application allows you to transform a function that takes n parameters to a function that takes n-1 paramters.

* Another technique you can use to adapt functional APIs is to match each other is a technique known as currying, named for a mathematician Haskell Curry, it is similar to partical application. It just works at a slightly different level of indirection.
    * With currying, you can transform a function that take n parameters into a function that you invoke to apply a parameter and you get back as a result a function that takes n-1 parameters. You can think of it as a function that will do a partial function application instead of immediantly doing the partial application.