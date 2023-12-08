# Amazon Simple Notification Service (Amazon SNS)

#essentials 

[Amazon Simple Notification Service (Amazon SNS)](https://aws.amazon.com/sns/) sends notifications two ways, A2A and A2P. A2A provides high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications. These applications include [[Amazon SQS|Amazon Simple Queue Service (SQS)]], [[Amazon Kinesis|Amazon Kinesis Data Firehose]], [[AWS Lambda]], and other HTTPS endpoints. A2P functionality lets you send messages to your customers with SMS texts, push notifications, and email.

Amazon Simple Notification Service (Amazon SNS) is a pub/sub service. Using Amazon SNS topics, a publisher publishes messages to subscribers. Subscribers can be web servers, email addresses, [[AWS Lambda]] functions, or several other options.

Two examples of how to use Amazon SNS:
- Publishing updates from a single topic
- Publishing updates from multiple topics