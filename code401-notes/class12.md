# Class 12

What is a Web Socket?

- A Web Socket is a communication protocol that provides full-duplex communication channels over a single TCP connection. It allows for real-time, bidirectional communication between a client (typically a web browser) and a server.

Describe the Web Socket request/response handshake and what happens once the connection is established.

- The Web Socket handshake begins with an HTTP request from the client to the server, containing an "Upgrade" header with the value "websocket". If the server supports Web Sockets, it responds with an HTTP 101 status code, indicating a successful upgrade. Once the connection is established, both the client and server can send messages to each other asynchronously without the overhead of HTTP request/response cycles.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

- Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client.

What does the event handler io.on() do?

- The io.on() event handler in Socket.IO is used to listen for events emitted by clients or servers. It allows developers to define functions to handle specific events, such as incoming messages or connections.

Describe some possible proof of life or proof that the code works as expected

- Some possible proofs of life for code using Web Sockets or Socket.IO could include:

Testing the real-time exchange of messages between client and server.
Monitoring server logs for incoming connections and emitted events.
Using debugging tools to inspect the data being sent and received.
Implementing error handling and logging to track any unexpected behavior.

What does socket.emit() do?

- socket.emit() is a method in Socket.IO that allows a client or server to emit custom events and data to the other party. It sends data along with an event name to the receiving end, which can then handle the event and process the data accordingly.

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- WebSocket is a communication protocol standardized by the IETF, while Socket.IO is a library for real-time web applications built on top of WebSocket, with additional features such as multiplexing, broadcasting, and automatic reconnection handling. Comparing them is like comparing Git, a version control system, to GitHub, a platform built on top of Git that adds collaboration features.

When would you use Socket.IO?

- Socket.IO is suitable for applications that require real-time bidirectional communication between a client and a server, such as chat applications, online gaming, or collaborative editing tools. It provides a higher-level API than raw WebSockets, making it easier to implement features like room-based messaging and event handling.

When would you use WebSockets?

- WebSockets are used when you need real-time, low-latency communication between a client and a server, and you want to minimize the overhead of HTTP request/response cycles. They are suitable for scenarios where you need full-duplex communication, such as live sports updates, financial trading platforms, or monitoring systems. If you require additional features like automatic reconnection or broadcasting, you might consider using a library like Socket.IO instead.