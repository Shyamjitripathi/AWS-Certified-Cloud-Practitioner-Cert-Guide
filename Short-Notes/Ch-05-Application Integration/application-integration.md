# Application Integration

- AWS Step Functions : is a fully managed service that makes it easy to coordinate the components of
distributed applications and microservices using visual workﬂows.Step Functions provides a graphical console to arrange and visualize the components of
your application as a series of steps. This makes it simple to build and run multi-step applications.
Step Functions automatically triggers and tracks each step, and retries when there are errors, so your
application runs in order and as expected. Step Functions logs the state of each step, so when things do
go wrong, you can diagnose and debug problems quickly. You can change and add steps without even
writing code, so you can easily evolve your application and innovate faster.
- Amazon AppFlow : is a fully managed integration service that enables you to securely transfer data
between Software-as-a-Service (SaaS) applications such as Salesforce, Zendesk, Slack, and ServiceNow,
and AWS services such as Amazon S3 and Amazon Redshift, in just a few clicks. With Amazon AppFlow,
you can run data ﬂows at enterprise scale at the frequency you choose - on a schedule, in response to a
business event, or on demand. You can conﬁgure data transformation capabilities such as ﬁltering and
validation to generate rich, ready-to-use data as part of the ﬂow itself, without additional steps. Amazon
AppFlow; automatically encrypts data in motion, and allows users to restrict data from ﬂowing over the
public internet for SaaS applications that are integrated with AWS PrivateLink, reducing exposure to
security threats.
- Amazon EventBridge : is a serverless event bus that makes it easier to build event-driven applications
at scale using events generated from your applications, integrated Software-as-a-Service (SaaS)
applications, and AWS services. EventBridge delivers a stream of real-time data from event sources
such as Zendesk or Shopify to targets such as AWS Lambda and other SaaS applications. You can set up
routing rules to determine where to send your data to build application architectures that react in real-
time to your data sources with event publisher and consumer completely decoupled.
- Amazon MQ : is a managed message broker service for Apache ActiveMQ and RabbitMQ that makes it
easy to set up and operate message brokers in the cloud. Message brokers allow diﬀerent software
systems–often using diﬀerent programming languages, and on diﬀerent platforms–to communicate
and exchange information. Amazon MQ reduces your operational load by managing the provisioning,
setup, and maintenance of ActiveMQ and RabbitMQ, popular open-source message brokers. Connecting
your current applications to Amazon MQ is easy because it uses industry-standard APIs and protocols for
messaging, including JMS, NMS, AMQP, STOMP, MQTT, and WebSocket. Using standards means that in
most cases, there’s no need to rewrite any messaging code when you migrate to AWS.
- Amazon Simple Notiﬁcation Service : is a highly available, durable, secure, fully managed
pub/sub messaging service that enables you to decouple microservices, distributed systems, and
serverless applications. Amazon SNS provides topics for high-throughput, push-based, many-to-many
messaging. Using Amazon SNS topics, your publisher systems can fan out messages to a large number of
subscriber endpoints for parallel processing, including Amazon SQS queues, AWS Lambda functions, and
HTTP/S webhooks. Additionally, SNS can be used to fan out notiﬁcations to end users using mobile push,
SMS, and email.
- Amazon Simple Queue Service : is a fully managed message queuing service that enables
you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates
the complexity and overhead associated with managing and operating message oriented middleware,
and empowers developers to focus on diﬀerentiating work. Using Amazon SQS, you can send, store, and
receive messages between software components at any volume, without losing messages or requiring
other services to be available. Get started with Amazon SQS in minutes using the AWS Management
Console, AWS CLI, or SDK of your choice, and three simple commands. Amazon SQS oﬀers two types of message queues. Standard queues oﬀer maximum throughput, best-
eﬀort ordering, and at-least-once delivery. Amazon SQS FIFO queues are designed to guarantee that
messages are processed exactly once, in the exact order that they are sent.
