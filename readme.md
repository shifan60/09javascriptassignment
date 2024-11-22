   Javascript Assignment-9

1. Explain the scope in Javascript  :- JavaScript have 3 types of scope :

 . Block scope :-Variables declared inside a curly braces ({ })block cannot be accessed from outside the block:
 . Function scope :-Variables defined inside a function are not accessible (visible) from outside the function.
   Variables declared with var, let and const are quite similar when declared inside a function and They all have Function Scope
 . Global scope :- Variables declared Globally (outside any function) have Global Scope.Global variables can be accessed from anywhere in     a    JavaScript program.Variables declared with var, let and const are quite similar when declared outside a block.

2. What is a callback ?

  .  Where callbacks really shine are in asynchronous functions, where one function has to wait for another function.

3. Explain context in JavaScript ?

  .  JavaScript Execution Context is the environment in which JavaScript code is executed. It contains information about the variables, functions,  and objects that are available to the code being executed, as well as the scope chain and the value of the 'this' keyword

4. What is hoisting in JavaScript?

  .  It is a mechanism where the declaration of variables and function are taken to the top of the scope all before the execusion of the code.

5. Explain lexical scope ?

  .  The area where the variables and their values are accessibleduring the execusion of code.

6. What is scope chaining?

  .  The scope chain in JavaScript is formed when functions are nested within other functions. Each function in JavaScript has access to its own variables, as well as variables from its parent functions. This forms a chain of scopes that allows inner functions to access variables from outer functions.

7. Explain closure ?

  .  Is the combination of functionand it's lexical environment with in which the function is declared .

8. What is the difference between undefined and not defined in javascript ?

  .  undefined :-  A variable that has been declared but not assigned a value is undefined .

  .  not defined :- A variable that has not been declared at all is not defined .

9. Explain spread and rest operator ? 

  .  spread operator :-   The spread operator, denoted by three consecutive dots (...), is primarily used for expanding iterables like arrays into individual elements. This operator allows us to efficiently merge, copy, or pass array elements to functions without explicitly iterating through them.
  
  .   rest operator :-The Rest Operator
While the spread operator expands elements, the rest operator condenses them into a single entity within function parameters or array destructuring. It collects remaining elements into a designated variable, facilitating flexible function definitions and array manipulation.

10. Explain ‘this’ keyword in Javascript ? 

  .  The 'this' keyword refers to the context where a piece of code, such as a function's body, is supposed to run .

 
