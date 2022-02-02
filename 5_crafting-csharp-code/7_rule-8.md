# Rule #8 - Avoid Boolean Parameters

* The 8th rule to to avoid boolean parameters that are flags to a function, because they don't look good in the code that has to call the method, and this goes back to readability.
* For example, when you look at the code that has to invoke this method, you see the false value hanging at the end (for example, `storage.WriteFile(data, false);`) and you have to wonder, what does it do?? Can you break the method up into more to make it crystal clear?