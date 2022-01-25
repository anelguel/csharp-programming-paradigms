# Why Dynamic?

* Dynamic Languages? What does it mean to by dynamic?
    * Computer science divides languages into two categories: static and dynamic languages
    * Static: C/C++, Java, C#, F#, Haskell
    * Dynamic: JavaScript, Ruby, Python, PHP, Perl
* The lines are sometimes blurry because some languages, like C#, have featuers that fall into both categories

* Generally speaking, a dynamic language will allow you to modify code and modify types at runtime. Some languages like JavaScript, Ruby, and Python do not have a traditional compiler or a compilation phase. So they don't perform type checking until the program runs, if they perform type checking at all.
    * Many dynamic languages coheres and convert types at runtime to keep an application running.

* Static languages: has a compiler, static type checking at compile time, so the compiler will raise an error if we try to assign a string to an interger value, for example.
* With static languages when you define a class with a property of type string, every object using this class will have a property of type string. There is no way to change an object to change of add a new propery without changing the definition in the source code and recompiling.
* With dynamic languages that uses classes like Ruby, I'd be able to change object instantiated from a class definition. I could remove properties and methods or add properties and methods. In fact, most languages will also let me change the definition of a class on the fly at runtime without recompiling, and then all new objects created from the class definition will have the changes I made dynamically.
* Everything in software development is about tradeoffs
    * Dynamic languages have a great deal of flexibility