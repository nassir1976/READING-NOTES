[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-14
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
- FIFO Queue
  - A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives.

- Pub/Sub

  - Pub/sub is shorthand for publish/subscribe messaging, an asynchronous communication method in which messages are exchanged between applications without knowing the identity of the sender or recipient.