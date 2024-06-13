# Class 34

Explain the different between a query string parameter and a path parameter.

Query String Parameter:

- A query string parameter is part of the URL that comes after a question mark (?).
- It is typically used to filter or modify the data returned by an API.

Path Parameter:

- A path parameter is part of the URL path itself, defined by placeholders in the path.
- It is used to identify specific resources.

What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com

- http://our-site.com/v3/stuff/things

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

- An interface in an API is like the librarian who helps you find what you need. Instead of manually searching for each item, you tell the librarian (the interface) what you're looking for, and they provide it to you quickly.

Describe how you would use middleware to implement basic and bearer auth.

- Middleware is like a security guard in a building that checks your ID before you enter.
- The middleware reads the Authorization header of the request, It checks if the header contains a username and password.
- If the credentials are correct, the request is allowed to proceed. 

Describe the handshake necessary to implement OAuth.

- Client Requests Authorization
- User Grants Permission
- Client Requests Token
- Server Grants Token
- Client Accesses Resources

Describe how Role Based Access Control works to a non-technical friend.

- In a company where different employees have different keys, these keys give access to different rooms based on their roles. With RBAC, you’re assigned a role, and that role determines what you can access and do within the system. This way, not everyone can access everything, only what they need for their role.