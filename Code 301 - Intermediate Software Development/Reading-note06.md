[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-6

### Node, Express, and APIs
- Node.js, a JavaScript runtime for building server-side or desktop applications.
- Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine.
- Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.
- node.js was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.
 ### Node-Specific Functionality
Node provides access to several important global objects for use with Node program files. When writing a file that will run in a Node environment, these variables will be accessible in the global scope of your file.

- module is an object referring to the functionality that will be exported from a file. In Node, each file is treated as a module.
- require() is a function used to import modules from other files or Node packages.
- process is an object referencing to the actual computer process running a Node program and allows for access to command-line arguments and much more.
ode’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections.

 ### npm, the JavaScript Package Manager
- Node comes bundled with a package manager called npm.
 ### What Is Node.js Used For?
- Node. js is a runtime env ironment that executes JavaScript on the server side. Being a frontend programming language, JavaScript uses a single thread to process tasks quickly.

### node.js is event loop .

                            Node’s execution model:
                            
                            1) node apps pass async tasks along with a callback   (function , callback).
                              
                            2) the event loop efficiently manages a thread poool and excute task efficiently .
                            
                            3) and excute each callback as task complete.
 ### Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.
 
Attribution : https://www.sitepoint.com/an-introduction-to-node-js/