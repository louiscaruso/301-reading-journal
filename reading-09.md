# Reading 09

## What is functional programing?
- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## Pure functions
- It returns the same result if given the same arguments 
  - Imagine we want to implement a function that calculates the area of a circle. An impure function would receive radius as the parameter, and then calculate `radius * radius * PI:`
    ```
      let PI = 3.14;

      const calculateArea = (radius) => radius * radius * PI;

      calculateArea(10); // returns 314.0
    ```
- It does not cause any observable side effects
- Pure functions benefits
  - The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
   - Given a parameter A → expect the function to return value B
   - Given a parameter C → expect the function to return value D

## Functions as first-class entities
- The idea of functions as first-class entities is that functions are also treated as values and used as data.
- Functions as first-class entities can:
  - Refer to it from constants and variables
  - Pass it as a parameter to other functions
  - Return it as result from other functions

## Refactoring

- Refactoring can extend the life of source code, preventing it from becoming legacy code
- The refactoring process makes future enhancements to such code a more pleasant experience
- Refactoring is also known as reengineering
- Refactoring includes many elements, such as:
  - Modularizing chunks of code and how to structure those modules
  - Refactoring helps make it more readable
  - Sticking to standards like naming conventions and code structure

