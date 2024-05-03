# Class 5

## Tutorial: How to Use Arrow Functions in JavaScript

### What are Arrow Functions?

- Arrow functions, introduced in ES6, provide a concise syntax for writing JavaScript functions. They offer a shorter syntax compared to traditional function expressions and do not bind their own this, arguments, super, or new.target.

### Why Use Arrow Functions?

- Conciseness: Arrow functions can make your code more readable and reduce boilerplate.
- Lexical this Binding: Arrow functions lexically bind the value of this. This means that they inherit the this value from the enclosing scope.

### How to Use Arrow Functions?

// Traditional function expression

function double(x) {
  return x * 2;
}

// Arrow function
const doubleArrow = (x) => x * 2;

console.log(double(3)); // Output: 6
console.log(doubleArrow(3)); // Output: 6
