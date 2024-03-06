# Class 13

Why would a developer use local storage for a web application?
- Persistent Client-Side Storage
- Storing data locally can reduce the need to repeatedly fetch information from the server. 
-  Local storage is particularly useful for enabling offline access to web applications.

What information should not be stored in local storage?
- Avoid storing sensitive personal information
- Critical Business Logic or Algorithms
- Large Amounts of Data due to limitations

Local storage can store what type of data? How would you convert it to that type before storing?
- Local storage in web browsers is designed to store data as strings. toString() or You can work around this by using the native JSON.stringify() and JSON.parse() methods: