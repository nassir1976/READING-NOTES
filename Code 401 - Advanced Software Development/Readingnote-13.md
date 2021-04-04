[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-13
### Readings: Message Queues

- Review, Research, and Discussion

1- What does it mean that web sockets are bidirectional? Why is this useful?
- web sockets are bidirectional means it hanndles both client-side and server-side.
- Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

2- Does socket.io use HTTP? Why?
-  no, Socket.IO is always dependent on a http server

3- What happens when a client emits an event?
- he event gets passed to the server through websockets. Its a tcp connection from the browser to the server. The connection is full duplex meaning the server can send real time data to the client and vise versa.

4- What happens when a server emits an event?
-when the server listen to the connection event. When that event is invoked, socket.io pass a socket object to our function. We then listen to all of our sockets for a chat. As defined on the client side, take the data emited from the chat and emit it back to all of our sockets.

5- What happens if a client “misses” an event?
- it stored in queue until the client get opportunity to listen the event.
6- How can we mitigate this?
 we will push a missed event to the Buffers until it is consumed(used).

### Document the following Vocabulary Terms
#### Term
- Socket
  - a socket is an endpoint of a communication between two programs running on a network. Sockets are used to create a connection between a client program and a server program
- Web Socket

  - The WebSocket object provides the API for creating and managing a WebSocket connection to a server, as well as for sending and receiving data on the connection.

- Socket.io
   - Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.
- Client
   - The Clients interface provides access to Client objects.
- Server
   - framework can be used to develop web servers using the 'http' module.
- OSI Model
   - The OSI model is an architectural model that represents networking communications.
- TCP Model
   - TCP (Transmission Control Protocol) is a protocol for sending information between computers.
- TCP
  - TCP (Transmission Control Protocol) is a protocol for sending information between computers.
- UDP
   - UDP (User Datagram Protocol) is a long standing protocol used together with IP for sending data when transmission speed and efficiency matter more than security and reliability.

- Packets


 