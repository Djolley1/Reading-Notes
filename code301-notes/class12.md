# Class 12

In your own words, describe what each group of status code represents:

100’s = 100 range are informational responses.

200’s = 200 range indicate that the client's request was successfully received, understood, and accepted by the server.

300’s = 300 range indicate that further action needs to be taken to complete the request.

400’s = 400 range indicate that there was an error on the client's side, such as a bad request or authentication failure.

500’s = 500 range indicate that there was an error on the server's side while processing the request.

What is a status code 202? 

- This code tells the client that the request was valid, but its processing will finish sometime in the future.

What is a status code 308? 

- This tells the client to use another URL to access the resource and not use the current URL anymore.

What code would you use if an update didn’t return data to a client?

- 204 No Content.

What code would you use if a resource used to exist but no longer does?

- 410 Gone.

What is the ‘Forbidden’ status code?

- code 403.

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

- Storing sensitive information directly within server-side code can pose security risks.

What is middleware?

- software that acts as a bridge between an application and its underlying operating system, network, or other applications.

What does app.use(express.json()) do?

- parses incoming requests with JSON payloads.

What does the /:id mean in a route?

- it means that the route expects a parameter called id to be passed in the URL.

What is the difference between PUT and PATCH?

- when you use PUT, you send a complete representation of the resource you want to update.
- With PATCH, you send only the fields that need to be updated, along with their new values.

How do you make a default value in a schema?

- To set a default value in a schema, you simply specify the value you want a field to have if no other value is provided.

What does a 500 error status code mean?

- Internal Server Error, indicates that something unexpected went wrong on the server while it was trying to fulfill a request from the client.

What is the difference between a status 200 and a status 201?

- The 200 status code indicates that the server successfully processed the client's request and returned the requested resource.
- The 201 status code is used to indicate that a new resource has been successfully created on the server as a result of the client's request.
