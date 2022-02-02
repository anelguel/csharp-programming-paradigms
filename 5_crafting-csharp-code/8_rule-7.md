# Rule 7 - Avoid Too Many Parameters

* The question is, how many is too many? The author recommends keeping it at max three.
* When you see four or more parameters, it begs the question, what is the relationship between those parameters? Because if they're coming into this method at the same time, there usually means that there is some relation. Are they grouped together in other places?
    * It's possible that this is a class definition waiting to sprout from, for example, a method with four parameters