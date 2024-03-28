# Class 04

What is a ‘Controlled Component’?

- In React, a "controlled component" refers to a form element like an input, textarea, or select whose value is controlled by React state.

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- Storing responses as users enter them allows you to perform real-time validation. You can immediately give feedback to users if their input is invalid, improving the overall user experience.

How do we target what the user is entering if we have an event handler on an input field?

- When you have an event handler on an input field, you can access the value that the user is entering through the event object passed to the event handler function.

Why would we use a ternary operator?

- The ternary operator is a concise way to write conditional statements in many programming languages, including JavaScript.

Rewrite the following statement using a ternary statement:

- console.log(x === y ? true : false);