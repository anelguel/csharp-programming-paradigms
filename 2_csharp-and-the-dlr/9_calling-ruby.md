# Calling Ruby

* Dynamic Language Interop: IronRuby, IronPython, Clojure. Sometimes these languages are better suited to solve a problem, so the ability to call Python code from C#, can be an advantage and time saver in some projects.
* To do this, for example with IronRuby, you first need to go to `ironruby.net` and download the binaries. This will give you everything you need to execute Ruby code. 
    * If you're working with Visual Studio, you'll also need to download the Ruby Tools for Visual Studio. 
        * This means you can rub Ruby project in VS, step through Ruby code with the debugger, and you have the editor to edit the code.
        * File > New Project > you'll see some Ruby options, files will end with `.rb`.
        * When bring Ruby code in, you first need to bring in a Ruby engine (`var engine = IronRuby.Ruby.CreateEngine();`), and then you can tell it to execute code in a specific file/place (`engine.CreateScope();`).