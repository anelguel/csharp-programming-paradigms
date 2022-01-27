# Lazy Code

* Also called "lazy evaluations" allows you to write an expression that doesn't execute until the last possible moment. And it only executes if the program forces it to execute. In other words, you actually need the result. Lazy functions are functions that do the least amount of work needed to produce the proper results.
* Lazy code can sometimes allow you to avoid expensive calculations that you don't need. 
* Lazy code can also make your code work with data structures that have an infinite size.

* What if you need to find a given value in a dataset of 10,000? Instead of running through each individual number, this is where the `yield` keyword comes in.
    * When you use `yield return` in a method, the C# compiler will generate the code for an object that implements `IEnumberable`. And that object will allow a caller to use `foreach` or `GetEnumerator` to enumerate through the results you are producing from this method.
    * Effectively, `yield return` pauses the execution of the method and let the caller process the current result. And later, when the caller needs the next result, the execution will pick up where it last left off.
