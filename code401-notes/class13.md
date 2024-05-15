# Class 13

Explain to a non-technical recruiter what the Chat Example (above) does.

- web application that allows multiple users to communicate in real-time through messages. It uses a technology called Socket.IO to enable this real-time communication between users and the server.

What proof of life are we getting on the backend from the above app?

- Proof of life" in this context means that the server is active and able to communicate with connected clients. We get this by seeing messages being sent and received successfully.

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

- socket.broadcast.emit('eventName', data);

What is a room and how might a room be useful?

- A room is a grouping mechanism provided by Socket.IO that allows you to create isolated channels within a single namespace. It can be useful to group users who are part of the same conversation or topic.

How do you join a room?

- socket.join('roomName');

how do you leave a room?

- socket.leave('roomName');

What is a Namespace and what does it allow you to do?

- A namespace is a way to split the Socket.IO server into separate communication channels, each with its own logic. It allows you to create different endpoints for different functionalities within the same server.

Each namespace potentially has its own what? (hint: 3 things)

- Event handlers
- Middleware
- Rooms

Discuss a possible use case for separate namespaces

- Separate namespaces can be useful in a scenario where you have different parts of an application that require distinct real-time communication logic.
