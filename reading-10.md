# Reading 10- The Call stack and debugging

## The call stack
- A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function
  ```
      function greeting() {
      // [1] Some codes here
      sayHi();
      // [2] Some codes here
    }
    function sayHi() {
      return "Hi!";
    }

    // Invoke the `greeting` function
    greeting();

    // [3] Some codes here
  ```
## Understanding the Call stack
- The call stack is primarily used for function invocation. Since the call stack is single, function execution is done, one at a time, from top to bottom. It means the call stack is synchronous.

- A call stack is a data structure that uses the Last In, First Out principle to temporarily store and manage function invocation

- A stack overflow occurs when there is a recursive function without an exit point. The browser has a maximum stack call that it can accommodate before throwing a stack error  

## Error Messages and Debugging
- Error messages are something that developers will expect when building their own application. The more times you run into errors and solve them, the more experience you get and saves you time.

- `Console.log()` is your best bet to figure out what is wrong.

- Try and Catch is a method that we learned when working with our project.

- Utilize tools such as quokka and eslint to aid with finding errors in your code.
Reference Errors

- As simple as when you try to use a variable that is not yet declared you get this type of error
Syntax Errors

- This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse
Range Errors

- Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up
Type Errors

- This type of error shows up when the types you are trying to use or access are incompatible, like accessing a property in an undefined type of variable
