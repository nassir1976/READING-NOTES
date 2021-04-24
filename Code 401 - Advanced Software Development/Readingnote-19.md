[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-19
###  AWS: Events

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
- Serverless API
    - Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider.

- Triggers
    - A trigger is a stored procedure in database which automatically invokes whenever a special event in the database occurs

- Dynamo vs Mongo
      - DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions
      
- Dynamoose vs Mongoose