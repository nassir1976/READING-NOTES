[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-11

## Reading: Socket.io


- Review, Research, and Discussion

1. What is the benefit of transforming data into packets?
 -  meet the demands of pervasive data-centric applications and services.
 - most cost-effective, efficient, and scalable networks for content delivery.
 - redundancies for full visibility

2. UDP is often refereed to as a connectionless protocol. Why is this?
-UDP is a connectionless protocol. No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted. As a result, the application must take care of data integrity all by itself.

3. Can a socket server application have multiple socket connections?
- A server socket listens on a single port has Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to
4. Can a socket connection application be connected to multiple socket servers?

-  server socket listens on a single port. All established client connections on that server are associated with that same listening port on the server side of the connection. An established connection is uniquely identified by the combination of client-side and server-side IP/Port pairs. Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

5. Can an application be both a socket server and a socket connection?

- You can't have two client sockets connect to each other in TCP, as the low-level connection protocol doesn't work that way.

### Document the following Vocabulary Terms
### Term
- Observer Pattern

 The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

- Listener

An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard

- Event 

A function or method containing program statements that are executed in response to an event. An event handler typically is a software routine that processes actions such as keystrokes and mouse movements. With Web sites, event handlers make Web content dynamic

- Event Driven Programming

event-driven programming is when a program is designed to respond to user engagement in various forms. It is known as a programming paradigm in which the flow of program execution is determined by “events.” Events are any user interaction, such as a click or key press, in response to prompt from the system.

- Event Loop

The Event Loop has one simple job — to monitor the Call Stack and the Callback Queue. If the Call Stack is empty, the Event Loop will take the first event from the queue and will push it to the Call Stack, which effectively runs it. Such an iteration is called a tick in the Event Loop.

- Event Queue

An event queue is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system.
- Call Stack

a call stack is a stack data structure that stores information about the active subroutines of a computer program
- Emit/Raise/Trigger

The trigger() method triggers the specified event and the default behavior of an event (like form submission) for the selected elements. This method is similar to the triggerHandler() method, except that triggerHandler() does not trigger the default behavior of the event.
- Subscribe

This is a JavaScript object that defines the handlers for the notifications you receive. The subscribe() call returns a Subscription object that has an unsubscribe() method, which you call to stop receiving notifications.
- database

A database is a data structure that stores organized information

source:https://stackoverflow.com/questions