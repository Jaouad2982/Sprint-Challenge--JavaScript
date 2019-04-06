/*

1- The difference between forEach and map.
    The forEach method does not return, it simply calls a function on each element of the array.
    The map method does have a return statement, It return an array of the same size.
    
2-A method is a function that is declared within an object, the function can also be method if it is declared on the global scope but bound 
    to the window object or called like this window.nameAfunction()
    A function can be of different forms anonymous, expression, declaration,Functions are executed when they are called. Values can be passed into functions and used within the function
    
3- A closure is an inner function that has access to the outer functions around it and their variables.
    it is the combination between the function and the lexical env it was declared in.
    
4-the four rules of this
    * window binding
        When in the global scope, the value of “this” will be the window/console Object
    * implicit binding
       Implicit binding occurs when dot notation is used to invoke a function. 
       In implicit binding, whatever is to the left of the dot becomes the context for this in the function.
    * explicit binding
        Explicit binding of this occurs when .call(), .apply(), or .bind() are used on a function.
        We call these explicit because you are explicitly passing in a this context to call() or apply().
    * using the new keyword(binding with new).
        if a function was called with new, the this keyword is referencing that new object that the interpretor created.

    
5- you need super() to be able to inherit the parents proprieties and attributes.   

*/
