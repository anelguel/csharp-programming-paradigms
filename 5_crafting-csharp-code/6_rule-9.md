# Rule 9 - Use Exceptions for Errors

* ... instead of status code or booleans
* ... but not for control flow

* Rule #9 is to throw an exception when there is a runtime error condition and do not use boolean return values or even worse status codes to tell a caller about an error.
* There is a place where you do not want to use exceptions and that is to implement regular control flow. So instead of using a break, or a return statement, or some other mechanism to jump out of a method and return to the caller,  you just through an exception that you plan to catch somewhere else in the code. That's a bad idea.
    * Exceptions should only be used to indicate an error in the program. And if you use them to jump around in code, you'll be making the code very hard to follow, read, and understand.