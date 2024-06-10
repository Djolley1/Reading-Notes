# Class 31

Summarize the five principles for structuring state.

- Group related state: Combine state variables that always update together into a single state variable.
- Avoid contradictions in state: Structure state to prevent contradictory values and "impossible" states.
- Avoid redundant state: Do not store derived values in state if they can be calculated from props or other state variables.
- Avoid duplication in state: Prevent the same data from being duplicated in multiple state variables or within nested objects.
- Avoid deeply nested state: Structure state in a flat way to simplify updates and avoid deep nesting complexities.

What problem do Contexts aim to solve?

- Contexts aim to solve the problem of prop drilling by providing a way to share values (such as data or functions) between components without having to explicitly pass props through every level of the component tree.

What is one technique to try before useContext?

- Before using useContext, try lifting state up to a common ancestor component and passing down props to the necessary child components.

What hook complements useContext for complex applications?

- The useReducer hook complements useContext for complex applications, helping to manage state logic and updates more effectively.
