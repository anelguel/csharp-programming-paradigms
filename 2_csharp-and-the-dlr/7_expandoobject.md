# ExpandoObject

* `Expando` is like a dictionary of string and object. You can use it by using the namespace `using System.Dynamic;` and when you create a new instance of `ExpandoObject`, you have the ability to just arbitrarily add things into the object (like properties and methods). That means you can just add it in the future using the `.` operator.