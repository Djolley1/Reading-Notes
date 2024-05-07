# Class 06


Safely Hashing and Storing a Password

- To keep passwords safe, we use a process called hashing. It's like turning the password into a scrambled code that can't be unscrambled easily. We then store this scrambled code instead of the actual password. So, when someone logs in, we hash the password they provide and compare it with the stored scrambled code. If they match, the login is successful.

Bcrypt

- Bcrypt is a type of hashing algorithm designed specifically for passwords. It's popular because it's slow, making it hard for attackers to guess passwords quickly. Slowing down the process helps protect against brute-force attacks, where attackers try many possible passwords until they find the right one.

Basic Authentication

- Basic Authentication is a simple way for a user to prove their identity when accessing a website or service. When you use Basic Auth, your username and password are sent to the server, but they're encoded to prevent easy reading. However, Basic Auth isn't very secure on its own because the encoded credentials can be easily decoded.

Properties in the Header of a Basic Auth Request

- The "Authorization" header is necessary.
It starts with the word "Basic" followed by a space and then the encoded username:password.
Encoding Username:Password
The username and password are combined with a colon (:) and then encoded using Base64 encoding.

Authentication Process

- When you log in, you provide your username and password. The system checks if they match what's stored. If they do, you're allowed access. If not, you're denied. It's like showing your ID at a club. If it matches their records, you're in; if not, you're turned away.

Error Messaging

- For HTTP errors, it's important to use status codes that indicate the nature of the error (like 401 for unauthorized access). In HTML, clear messages should inform users of what went wrong (e.g., "Incorrect username or password"). Good error handling helps users understand and correct their mistakes.

OWASP

- OWASP (Open Web Application Security Project) provides guidelines for building secure applications. Following these principles helps prevent common security vulnerabilities. It's like building a house with strong locks and alarms from the start, so it's harder for burglars to break in later.

