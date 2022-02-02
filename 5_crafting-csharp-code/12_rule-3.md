# Rule 3 - Try To Avoid Comments

* Topic up for debate
* Most comments are trying to describe the purpose or intention of a piece of code. The author would rather rewrite the *code* to be more intention revealing to the point where the comment is unnecessary. Can it be a method with a descriptive method name?
* The exception: `///` these comments are for documenting APIs. They allow you to document parameters and return values. Through this, other developers can see you comments in Intellisense when they reference your Assembly. This is nice for shared libraries. Keep them well maintained and updated.
* For other comments? Find a way to write the code without comments.