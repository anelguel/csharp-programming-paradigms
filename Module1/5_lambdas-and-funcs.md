# Lambdas and Funcs

* Microsoft created a new type to work with delegates, called `Func`. It is a generic type and it encapsulates delegates.
* With `Func`, the last parameter type is the return type. For example, `Func<int, bool>` takes an `int` and returns a `bool`.
* `Func<>` takes from 1 to 16 generic type parameters (so up to 15 input parameters, one return value).
* `Action<>` is just like `Func<>` except it has no return value; it returns void.
