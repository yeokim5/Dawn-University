
#### **Reading**

- **Functions as arguments**: Using higher-order functions like `summation` that take a term-generating function as an argument to compute summations like the sum of cubes.
> funtions can be used as arguments

- **Functions as general methods**: Illustrating how higher-order functions like `improve` can express general methods of computation, independent of the particular functions they call,
> def improve(update, close, guess=1):

- **Nested definitions**: Allowing functions to be defined inside other functions, enabling lexical scoping where inner functions can access variables from the environment they are defined in.


- **Functions as returned values**: Demonstrating how higher-order functions can return other functions, like function composition.
- **Examples**: Showing applications of higher-order functions for procedures like **Newton's** method for finding roots and **currying** functions.

- **Lambda expressions**: Introducing anonymous functions defined with the `lambda` syntax.

- **Abstractions and first-class functions**: Discussing how higher-order functions enable representing powerful abstractions directly in the programming language.

- **Function decorators**: Explaining Python's `@` syntax for applying higher-order functions to other functions during definition.



---


#### **Lecture**


Iteration: fibonacci number changining curr, pre can be useful including 0.

Designing Functions:
- give each function exactly one job
- don't repeat yourself
- define functions generally

Higher Order Functions: function that takes arument as functino
- Generalizing Patterns with Arguments: EX) sqaure, circle, hexagon using (r, shape_constant)

Functions as Return value:
- make_adder(2000)(13)
- f = make_adder(2000)
- f(13) >>> 2013

Lamda Expressions:
- (lambda x: x * x) (3) 
- has no return keyword(must be a single expression)

Return
- return if_(c,t,f) : if it's call expression, it can't skip evaulate all EX) sqrt(-4)

Control Expressions
- so i can use and return A and B : this will work
- or if want to use can express as conditional experession: 
> a if x else b

