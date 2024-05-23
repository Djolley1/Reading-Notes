# Class 19

Difference between SQS and SNS

Amazon SQS (Simple Queue Service):

- Message queuing service
- Ensures that each message is processed at least once
- Decouples sending and receiving components

Amazon SNS (Simple Notification Service):

- Pub/Sub messaging service
- Sends notifications to multiple subscribers (email, SMS, HTTP, etc.)
- Pushes messages to subscribers

Use Cases for SQS and SNS

SQS Use Cases:

- Order Processing: Decoupling order submission from order fulfillment
- Job Queues: Managing background processing tasks
- Batch Processing: Aggregating and processing data asynchronously

SNS Use Cases:

- Alert Systems: Sending alerts to multiple recipients (e.g., system failures)
- Push Notifications: Sending notifications to mobile devices
- Broadcasting Updates: Sending updates to multiple services or users

Using SQS and SNS in a “Fanout” Pattern

SNS Topic:

- Create an SNS topic.
- Publish messages to the SNS topic.

SQS Queues:

- Create multiple SQS queues.
- Subscribe these SQS queues to the SNS topic.

Message Flow:

- When a message is published to the SNS topic, it is automatically sent to all the subscribed SQS queues.
- Each SQS queue receives a copy of the message, allowing multiple consumers to process the message independently.

Push Notifications with SNS

Create an SNS Topic:

- Create a new SNS topic for push notifications.

Create Platform Applications:

- Create platform applications for different mobile platforms (iOS, Android).

Register Endpoints:

- Register mobile device endpoints with the platform applications.

Publish Messages:

- Publish messages to the SNS topic.
- SNS pushes the messages to the registered device endpoints, triggering push notifications on the devices.

Using a Queue System like SQS in a Large Scale, Distributed Application

Decoupling Services:

- Use SQS to decouple different components of the application.
- Each component can operate independently and asynchronously.

Load Balancing:

- Distribute workload evenly among multiple consumers.
- Scale consumers based on the size of the queue.

Error Handling:

- Use Dead Letter Queues (DLQ) to handle failed message processing.
- Ensure that no message is lost and can be reprocessed if necessary.

Resilience:

- Enhance system resilience by making sure that messages are stored durably and processed reliably.

Asynchronous Processing:

- Enable background processing of tasks, improving the responsiveness of the main application.
