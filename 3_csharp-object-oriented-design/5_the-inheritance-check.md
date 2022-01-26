# The Inheritance Check
 
* In Scott Allen's opinion, encapsulation is good, same goes for polymorphism, but inheritance can sometimes create as many problems as it solves.
* The primary benefit of inheritance is code reuse. If I inherit from a base class, I can reuse the code in the base class, and effectively that code is part of my class.
    * But inheritance tightly binds two classes together. 
    * Some languages like C++, you can give mulitple inheritance (multiple base classes). In C# you can only do one. More might seem more flexible, but the reality is that it typically creates more problems. You can implement multiple interfaces, but you can only have one base class. 
    * Quite often, a derived class needs to know a lot about the details of the base class, and that creates rigidity. It's harder to make changes.