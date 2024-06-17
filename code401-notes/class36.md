# Class 36

Reading: Application State with Redux

What is the first principle of Redux? The first principle of Redux is that the state of the whole application is stored in a single JavaScript object known as the "store".

What is a store and what do we use our reducers for within that store? A store is a centralized place to manage the application state, and reducers are functions used within the store to specify how the state changes in response to actions.

Name three Redux store methods given to us by createStore and describe their use.

getState(): Returns the current state of the application.
dispatch(action): Sends an action to the store to update the state.
subscribe(listener): Registers a callback that gets called every time the state changes.

Explain to a non-technical recruiter what combineReducers() does and why it is useful. combineReducers() is a utility function that merges multiple smaller reducer functions into a single reducer, making it easier to manage and scale the application's state management by organizing the state logically.
