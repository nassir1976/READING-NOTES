[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-17
###  Event Driven Architecture

1- What’s the difference between a FIFO and a standard queue?

  - FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

   - FIFO (first-in-first-out) queues preserve the exact order in which messages are sent and received.
   - A standard queue is used for application where the throughput of messages is more important than the ordering of messages. For example, an application for user registration where the order of users registering is not that important than the number of users that can register,

2- How can the server be assured a message was properly received?

   - by reciving(responding) notification messge from the server to the client .

3- What classic design pattern is best represented by event driven programming?

- observer pattern 
   - It is mainly used for implementing distributed event handling systems, in "event driven" software. In those systems, the subject is usually named a "stream of events" or "stream source of events", while the observers are called "sinks of events". The stream nomenclature alludes to a physical setup where the observers are physically separated and have no control over the emitted events from the subject/stream-source. 
   attribute:https://en.wikipedia.org/wiki/Observer_pattern 

4- How do you test an event driven system?
  - There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.
   atribute:https://medium.com/dan-on-coding/testing-event-driven-systems-63c6b0c57517


### Document the following Vocabulary Terms
### Term
- Server Instances
    -  server instance is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based.
- Containers
     - A container is any receptacle or enclosure for holding a product used in storage, packaging, and transportation, including shipping.
- Cloud Services
     - Cloud services are services available via a remote cloud computing server rather than an on-site server. These scalable solutions are managed by a third party and provide users with access to computing services such as analytics or networking via the internet.
- Cloud Architecture
     - Cloud Architecture refers to the various components in terms of databases, software capabilities, applications, etc. engineered to leverage the power of cloud resources to solve business problems. Cloud architecture defines the components as well as the relationships between them. ... Cloud resources.
- AWS
     - Amazon Web Services (AWS) is the largest public cloud computing platform in the world and one of the pioneers of on-demand computing. AWS launched in 2006 with a simple queuing service for application developers and soon expanded to offer elastic compute, and simple storage services.
     
- EC2/Beanstalk vs Heroku