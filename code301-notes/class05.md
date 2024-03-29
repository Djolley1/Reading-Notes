# Class 05

What is the single responsibility principle and how does it apply to components?

- a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

What does it mean to build a ‘static’ version of your application?

- To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props.

Once you have a static application, what do you need to add?

- interactivity

What are the three questions you can ask to determine if something is state?

- Does it change over time?
- Is it necessary for the application's functionality or behavior?
- Does it need to be shared or accessed by multiple components or modules?

How can you identify where state needs to live?

- Often, you can put the state directly into their common parent.
- You can also put the state into some component above their common parent.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

What is a “higher-order function”?

- Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- In line 2 of the function greaterThan, a higher-order function is being returned

Explain how either map or reduce operates, with regards to higher-order functions.

- map is a higher-order function because it takes another function as an argument (the function to apply to each element of the array).
- reduce is also a higher-order function as it takes another function (the combining function) and an initial value as arguments.