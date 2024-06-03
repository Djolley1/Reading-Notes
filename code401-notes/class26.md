# Class 26

What are the building blocks of a React app?

- Components: Reusable pieces of UI.
- JSX: Syntax extension for JavaScript.
- Props: Data passed to components.
- State: Internal data managed within components.
- Lifecycle Methods: Functions that run at different stages of a component's lifecycle.
- Hooks: Functions that let you use state and other React features.

What is the difference between an HTML element and a React component?

- HTML Element: Basic building block of a web page (e.g., <div>, <span>).
- React Component: A function or class that returns a piece of UI, which can include HTML elements and other React components.

What is JSX and why do we use it?

- JSX: JavaScript XML, a syntax extension that allows writing HTML-like code within JavaScript.
- Why Use It: It makes writing React components easier and more intuitive by combining HTML with JavaScript logic.

Describe the process of embedding JavaScript expressions in JSX.

- Embedding: Use curly braces {} to embed JavaScript expressions within JSX.
- Example: <h1>{title}</h1> embeds the value of the title variable inside an <h1> element.

Does React or JSX have any special features for iteration or conditional logic?

- Iteration: Use JavaScript's array methods (e.g., .map()) within JSX.
- Conditional Logic: Use JavaScript's conditional operators (e.g., ternary operator condition ? true : false) within JSX.

How does React know to respond to a user’s inputs?

- Event Handlers: React uses synthetic events to handle user inputs. You define event handlers (e.g., onClick, onChange) and attach them to elements.

What word indicates that a React component manages data with a Hook?

- use: Hooks are prefixed with "use" (e.g., useState, useEffect).

How can two React components share data?

- Props: Pass data from a parent component to a child component via props.
- Context: Use React Context to share data globally across the component tree.
- State Management Libraries: Use libraries like Redux or MobX for more complex state sharing.

What are the three steps of refreshing a React UI?

- Trigger an Update: Update state or props.
- Re-render: React re-renders the component with the new state or props.
- Update the DOM: React updates the actual DOM to reflect the new component structure.

How do you trigger updates to a component after the initial render?

- Updating State: Use the setState function (in class components) or the useState hook (in functional components) to update the state.
- Props Change: Updates to props passed from a parent component can also trigger re-renders.

Does React recreate DOM nodes on every rerender?

- No: React uses a virtual DOM to efficiently update only the parts of the DOM that have changed.

After React has updated the DOM, what still needs to happen before the user sees the change?

- Browser Rendering: The browser needs to repaint the screen to reflect the updated DOM changes.
