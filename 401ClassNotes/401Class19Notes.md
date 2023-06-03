# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: AWS: Events

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

- SQS (simple queue service) and SNS (simple notification service) are both message services provided by AWS.  The SQS focuses on reliable message queuing and processing different components while SNS is designed to broadcast messages to multiple subscribers across different services.  
- Message fanout pattern can be designed to use both SNS and SQS.  This message published to an SNS topic is distributed to multiple SQS queues in parallel.

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

- In a "fanout" pattern, messages are published to an SNS topic, which then distributes the messages to multiple SQS queues, allowing each subscriber to consume the messages independently and concurrently.
- Using SNS, push notifications work by sending real-time messages from a server or application to mobile devices, leveraging various channels such as Apple Push Notification Service (APNS), Firebase Cloud Messaging (FCM), or other supported platforms, enabling timely delivery of notifications directly to users' devices.

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

- For large scale distribution applications the SQS system could be used to decouple different components and provide asynchronous processing.  So when a component needs to perform a time consuming task if can send a message to the SQS instead of directly invoking the service.

## Bookmark

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)

## Reflection

- Trying to understand how SNS and SQS work together but are also separate systems.

## Class Notes

## Things I want to know more about
