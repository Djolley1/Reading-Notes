# Class 02

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- Render

What is the very first thing to happen in the lifecycle of React?

- Mounting, When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- Constructor, Render, React Updates, componentDidMount, componentWillUnmount

What does componentDidMount do?

- This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here.

What types of things can you pass in the props?

- Data from a parent component to a child component.

What is the big difference between props and state?

- Props are used to pass data from parent to child components in a unidirectional flow.
- State is used to manage data that can change within a component and influence its rendering.

When do we re-render our application?

- Re-rendering of components occurs when certain conditions are met. Changes in Props or Changes in State

What are some examples of things that we could store in state?

- User Input, Data Fetching, Error Handling.
