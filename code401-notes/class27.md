# Class 27

Summarize the five steps of thinking in react.

Break the UI into a Component Hierarchy

- Identify all the components and subcomponents within your UI.
- Name each component and arrange them in a hierarchical structure.

Build a Static Version in React

- Create a non-interactive version of your application.
- Build components that render the UI based on your data model, using props to pass data from parent to child components.

Find the Minimal but Complete Representation of UI State

- Determine the minimal set of state that your application needs to manage.

Identify which data is state by asking:

- Does it change over time?
- Is it passed in from a parent component via props?

Identify Where Your State Should Live

- Determine which component(s) should own each piece of state.
- Identify all components that render something based on that state.
- Find their closest common parent component.

Add Inverse Data Flow

- Enable the flow of data from child components back to the parent components.
- Pass down event handlers from the parent component to the child components.
- Update the state in the parent component based on user interactions in the child components, ensuring two-way communication between components.

What is one reason a local variable isn’t sufficient for managing a React component?

- Local variables do not persist between renders. When a component re-renders, it initializes all local variables from scratch, losing any changes made during previous renders.

What is the argument to the useState hook, and what are the two parts of its return array?

- The only argument to the useState hook is the initial value of the state variable. For example, useState(0) initializes the state variable with the value 0.

How can Component A access state from Component B?

- Component A can access state from Component B by lifting the state up to a common parent component or by using state management solutions like the Context API or Redux.