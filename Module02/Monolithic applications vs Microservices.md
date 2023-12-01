### Monolithic applications
Applications are made of multiple components which communicate with each other to transmit data, fulfill requests, and keep the application running. If an application has tightly coupled components, which includes databases, servers, UI, business logic, and so on, it is considered a monolithic application. If a single component fails, other components and possibly the entire application fails.

### Microservices
With microservices, applications are loosely coupled. If a single component fails, the other components continue to work. The loose coupling prevents the entire application from failing. When designing applications on AWS, you can take a microservices approach by utilizing [[Amazon SNS]] and [[Amazon SQS]].