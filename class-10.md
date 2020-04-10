## JavaScript book, Ch. 10, “Error Handling & Debugging”

> * Order of Execution 
>   * to find a source of an error, it helps to knw how scripts are processed. (Order of Execution)
> * Execution Context - there is one global execution context, plus each functin creates a new execution context. They correspond to variable scope
>   * Every statement in the script lives in one of three execution contexts: global context(script but not function), function context(code being run within a function), eval context(text is exectuted like code in an internal function called eval())
>   * Variable Scope - Global Scope(outside a function) and Function-level(inside a function) scope 
> * The Stack - Javascript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks or piles the new function on top of the current task 
> * Execution and Context and Hoisting 
>   * Each time a script enters a new exectuion context, there are two phases of activity: 
>   * Prepare: the new scope created, variables, functions, arguments are created, the value of the this keyword is determined
>   * Execute: now it can assign values to a variable, reference functions and run their code, execute statements 
> * Hoisting - call functions before they have been declared and assign a value to a variable that has yet to be declared
> * Debugging is the process of finding errors. It involves a process of deduction
> * The console helps narrow down the area in which the error is located. So you can try to find the exact error 
> * Javascript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error
> * If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 
