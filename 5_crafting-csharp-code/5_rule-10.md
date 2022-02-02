# Rule #10 - Avoid Regions

* Regions are a feature of Visual Studio that allow you to surround blocks of code, and put those blocks into regions that you can give a name to and then you can collapse a region.
* The author's experience is that regions often hide ugly code, or classes that have exploded in size and responsibility
* Next time you want to use a region, take a step back and ask it it's possible that what you really need to do is breaking that code into separate classes.