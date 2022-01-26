# Little Abstractions

* One of the biggest dangers in design is building flexibility, layers, or classes than you need to reasonably solve a problem.
    * Design mantras:
        * YAGNI - You Ain't Gonna Need It
        * KISS -  Keep it Simple, Stupid
* Design should be iterative and be driven by immediant needs with some consideration for things that are going to change in the future. 
    * Having concrete cases or tests cases in test driven development is a great way to get instant feedback on what you really need for your software.
* Small abstractions are often good abstractions because they focus on one thing and they do it well. That makes them easy to understand and modify.
* It's good to keep input and output type operations separate from the rest of the logic in the application. The code that makes decisions should NOT also be the code that does something about those decisions.