# Class 03

Classes are a template for creating ____.

- objects

Can a class declaration be hoisted?

- When you declare a class using the class keyword, its name is hoisted to the top of the scope, but the class body is not initialized until the code execution reaches the actual declaration.

How would you describe a constructor and contextual “this” to a non-technical friend?

- The constructor is like the setup phase for your robot. It's where you define what your robot will be able to do and what it will look like.
- Think of "this" as a way for your robot to refer to itself.

Within Express, what does routing refer to?

- outing refers to the process of defining how an application responds to client requests to specific endpoints and HTTP methods (GET, POST, PUT, DELETE).

What is the difference between a route path and a route method?

- A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.
- Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

- If next has been passed to your middleware as a parameter, you must call it to pass control to the next middleware in the stack. Failure to call next() within your middleware will result in the request being left hanging, causing your application to appear unresponsive.

What is an Express Router?

- It is a mini express application without all the bells and whistles of an express application, just the routing stuff.

By what mean do we initialize express.Router() in an express server?

- In an Express server, you initialize a router by calling the express.Router() function. This function returns a new router object which you can use to define routes for your application.

What do we use route middleware for?

- Route middleware in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we’d like to do before we actually spit out information to our user.
