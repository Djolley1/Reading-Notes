# Class 08

What does REST stand for?

- Representational State Transfer
- REST is an architectural style for building distributed systems based on hypermedia.

REST APIs are designed around a ____. 

- Set of architectural principles, with the central concept being the representation of resources.

What is an identifier of a resource? Give an example.

- a string of characters used to uniquely identify a particular resource on the internet.
- URL, URI

What are the most common HTTP verbs?

- GET, POST, PUT, PATCH, and DELETE.

What should the URIs be based on?

- URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

Give an example of a good URI.

- <https://api.example.com/v1/users/123>

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- A "chatty" web API refers to an API that requires a high number of small, fine-grained requests to accomplish a task.
- it's something to avoid

What status code does a successful GET request return?

- A successful GET method typically returns HTTP status code 200 (OK)

What status code does an unsuccessful GET request return?

- If the resource cannot be found, the method should return 404 (Not Found).

What status code does a successful POST request return?

- If a POST method creates a new resource, it returns HTTP status code 201 (Created)

What status code does a successful DELETE request return?

- If the resource doesn't exist, the web server can return HTTP 404 (Not Found).
