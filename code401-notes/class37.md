# Class 37

Readings: Redux - Combined Reducers
Why create multiple reducers? Creating multiple reducers allows for better organization and separation of concerns by managing different parts of the state independently.

How would you combine multiple reducers? You combine multiple reducers using the combineReducers function, which merges them into a single reducing function that manages the state tree.

How will you manage state as an immutable object? Why? State is managed as an immutable object to ensure that state changes are predictable and easier to track, which helps in debugging and maintaining the application.

combineReducers is a utility function to simplify the most common use case when writing ____ _____. Redux reducers.

Explain how combineReducers assembles the new state tree. combineReducers assembles the new state tree by delegating slices of state to the corresponding reducer functions, each managing its own section of the state tree.

How would you define initial state in an app using combineReducers? Initial state is defined by specifying initial values within each individual reducer function, which are then combined into the overall initial state tree.

Why will you want to split your reducing functions as your app becomes more complex? Splitting reducing functions helps manage the complexity by isolating logic related to different parts of the state, making the codebase more modular and maintainable.

The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to _____. combineReducers, createStore.

What is a popular convention when naming reducers? A popular convention is to name reducers after the part of the state they manage, often using the plural form of the noun (e.g., usersReducer, postsReducer).
