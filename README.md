# MountBlue-TechnicalPaper (MESSAGING QUEUE)

## What are Messaging Queues?
A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures. Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer. Message queues can be used to decouple heavyweight processing, to buffer or batch work, and to smooth spiky workloads.

A message queue is a component of messaging middleware solutions that enables independent applications and services to exchange information. Message queues store “messages”—packets of data that applications create for other applications to consume—in the order they are transmitted until the consuming application can process them. This enables messages to wait safely until the receiving application is ready, so if there is a problem with the network or receiving application, the messages in the message queue are not lost.

This model, known as asynchronous messaging, prevents data loss and enables systems to continue to function if processes or connections fail. This allows developers to keep processes and applications separate, keeping their communications self-contained and event-driven to make the architecture more reliable.

Message queues are available in messaging solutions across numerous deployment options, including optimized physical appliances, cloud services, mainframes, and as software.

## why they are used?
* Today’s enterprise computing environments are complex and highly decentralized. Messaging makes it easier to integrate applications and services on diverse platforms by providing a single, robust, and secure shared messaging backbone. This protects against data loss and ensures systems will continue to function even with unstable connectivity.

* Message queues are uniquely suited for integrating on-premises backend systems with cloud services. In cloud architectures, applications are often broken down into small, independent components. This makes it easier to design and code them, and also easier to manage their performance. Message queues enable these decoupled cloud-based applications to communicate with each other or with on-premises systems.

* Message queuing increases architecture resilience because the messages can have persistence. This means they’re stored to disk until the service receiving the message confirms processing. Messaging queues can be used in scenarios requiring high levels of security, fault tolerance, and accuracy, such as financial transaction processing, air-travel booking, or updating healthcare patient records.

* Message queues can also be used to enable applications and systems residing in different clouds (whether public or private) to communicate, even if they are located in different countries or even on remote continents. Using a message queue increases fault tolerance and can be used to prevent data being duplicated or lost across geographically and technically disparate systems. Because each service within the system is decoupled, or logically separated from the others, each can continue to function if other services or applications fail or stall.

* Message queues work across disparate applications such as mobile, IoT, and traditional transaction system records. They also support various platforms—such as virtual machines and containers—and can enable integration between legacy applications and today’s latest solutions.

## What are popular tools?
Some of popular tools for  Messaging Queues are:-
* Apache Kafka
* RabbitMQ
* Celery
* Nsq
* Redisson
* Apache ActiveMQ
* Vernemq

## What is Enterprise Message Bus?
An enterprise service bus (ESB) is a software platform used to distribute work among connected components of an application. It is designed to provide a uniform means of moving work, offering applications the ability to connect to the ESB and subscribe to messages based on simple structural and business policy rules.

As such, it's a tool that has use in both distributed computing and component integration. The best way to think of this tool is to visualize it as a set of switches that can direct a message along a specific route between application components based on message contents and implementation of business policies.

###References

- https://aws.amazon.com/message-queue/#:~:text=Message%20queues%20allow%20different%20parts,to%20send%20and%20receive%20messages.
- https://www.ibm.com/cloud/learn/message-queues
- https://blog.containerize.com/2021/07/09/top-5-open-source-message-queue-software-in-2021/
- https://www.techtarget.com/searchapparchitecture/definition/Enterprise-Service-Bus-ESB#:~:text=An%20enterprise%20service%20bus%20(ESB,structural%20and%20business%20policy%20rules.