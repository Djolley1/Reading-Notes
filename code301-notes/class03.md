# Class 03

What does .map() return?

- The .map() method itself returns a new array containing the results of calling the provided function on every element in the original array.

If I want to loop through an array and display each value in JSX, how do I do that in React? 

- In React, you can use the .map() method to loop through an array and display each value in JSX. 

Each list item needs a unique ____.

- Each list item in React should have a unique key prop.

What is the purpose of a key?

- The purpose of a key prop in React is to help React identify which items in a list have changed, been added, or been removed.

What is the spread operator?

- The spread operator, denoted by three consecutive dots (...), is a feature introduced in JavaScript (ES6) that allows an iterable (like an array or string) to be expanded into individual elements.

List 4 things that the spread operator can do.

- Copying Arrays
- Merging Arrays
- Passing Array Elements as Function Arguments
- Copying Objects (with Object Spread)

Give an example of using the spread operator to combine two arrays.

- const array1 = [1, 2, 3];
const array2 = [4, 5, 6];

const combinedArray = [...array1, ...array2];

Give an example of using the spread operator to add a new item to an array.

- const originalArray = [1, 2, 3];
const newItem = 4;

const newArray = [...originalArray, newItem];

Give an example of using the spread operator to combine two objects into one.

- const obj1 = { foo: 'bar' };
const obj2 = { baz: 'qux' };

const combinedObject = { ...obj1, ...obj2 };

In the video, what is the first step that the developer does to pass functions between components?

- Invoke the parent function

In your own words, what does the handleClick function do?

- handleClick is a simple function that logs a message to the console when it's called.

How can you pass a method from a parent component into a child component?

- you can pass a method from a parent component to a child component by passing it down as a prop.

How does the child component invoke a method that was passed to it from a parent component?

- when a method is passed from a parent component to a child component as a prop, the child component can invoke (call) that method by using the prop provided to it.