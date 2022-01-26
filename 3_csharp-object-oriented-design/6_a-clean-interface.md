# A Clean Interface

* Instead of inheritance, where things can get messy, we are going to use an interface definition which is a better solution.
* Inheritance is a perfect solution to some design problems. If you've ever used any of the UI frameworks in .NET, like Winforms, WPF, Silverlight, Web Forms, and even ASP .NET MVC in some circumstances, then you'll see that inheritance doing a good job.
* But *real* inheritance relationships rarely exist in a way that you can use inheritance in a uniform way.
* A interface definition is clean, because it doesn't specify any implementation details. An interface cannot even specify what type of constructor an object requires. 
* Interfaces are also great because they can be very small and very granular. A class can implement multiple interfaces and because of that we don't have to create an interface definition with loads of methods inside. We only need to present the methods that are related to the responsibility of that particular interface.