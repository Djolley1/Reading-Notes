# Class 18

What is Amazon API Gateway?

- Amazon API Gateway is a fully managed service provided by AWS that allows developers to create, publish, maintain, monitor, and secure APIs at any scale.

Why is Amazon API Gateway an important part of the Serverless ecosystem?

Amazon API Gateway is crucial in the Serverless ecosystem because it:

- Allows seamless integration with AWS Lambda, enabling the creation of fully serverless applications.

- Handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, authorization and access control, monitoring, and API version management.

- Simplifies the process of creating RESTful APIs, WebSocket APIs, and HTTP APIs, thus enabling developers to build scalable, secure, and performant APIs without managing infrastructure.

How does API Gateway integrate with other AWS services?

API Gateway integrates with other AWS services in several ways:

- AWS Lambda: Directly invokes Lambda functions in response to HTTP requests.
- Amazon DynamoDB: Allows direct interaction with DynamoDB tables, enabling CRUD operations without needing an intermediary.
- Amazon S3: Facilitates direct integration to store and retrieve objects.

What are some benefits of using Amazon API Gateway?

- Scalability: Automatically scales to handle traffic.
- Security: Offers robust security features like AWS IAM, AWS Cognito, and custom authorizers.
- Monitoring: Provides detailed monitoring and logging with AWS CloudWatch.

What two API types might you choose from?

- RESTful APIs: For traditional RESTful API design, suitable for CRUD operations and stateless interactions.
- WebSocket APIs: For real-time, two-way communication applications such as chat applications or streaming data.

What is DynamoDB?

- Amazon DynamoDB is a fully managed NoSQL database service provided by AWS that offers fast and predictable performance with seamless scalability.

Under what circumstances would you recommend DynamoDB over MongoDB?

- Serverless Architecture: When using a serverless architecture and needing seamless integration with AWS services.
- Scalability: When requiring automatic scaling and handling high traffic loads without manual intervention.
- Performance: When needing consistent, single-digit millisecond latency at any scale.

Explain to a non-technical friend how DynamoDB works.

DynamoDB is like this cabinet but supercharged. It helps you quickly find and store information without worrying about running out of space or the cabinet breaking down. You can add and retrieve items (data) really fast, and it can handle a lot of items without slowing down.

What is Dynamoose?

- Dynamoose is a modeling tool for Amazon DynamoDB that simplifies the process of working with DynamoDB in Node.js applications, providing a more intuitive and schema-based approach.

What are some key features of Dynamoose?

- Schema Modeling: Allows defining schemas for DynamoDB tables, making it easier to manage and validate data.
- Type Safety: Ensures data types are consistent and validated against the schema.
- High-Level API: Provides a simpler, more expressive API for database operations.
