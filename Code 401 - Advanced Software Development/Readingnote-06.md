
[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-06


### Readings: Authentication
#### Review, Research, and Discussion
1.Explain what a “Singleton” is (in Computer Science terms)

- A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object.

source:https://www.techopedia.com/definition/15830/singleton (Links to an external site.)

2.Explain how the Singleton pattern can be used with Node modules, specifically with classes

- A singleton is intended to provide only one instance of itself while facilitating a global point of access. Implementing a singleton pattern involves creating a class with a method that creates a new instance of the class. In order to implement a singleton pattern, principles of single instance and global access must be satisfied. The singleton class is like a global repository for an instance of itself, making the constructor private. Therefore, an instance outside the class cannot be created at all, and a singleton can contain only one instance. A singleton class instantiates itself and maintains that instance across systems.

3.If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

- Application Level Middleware

- Auth middleware

- Suppose we are having five routes getUsers,getDetails,updateDetails,isLoggedIn,isLoggedOut

- A middleware is basically a function that will the receive the Request and Response objects, just like your route Handlers do. As a third argument you have another function which you should call once your middleware code completed. This means you can wait for asynchronous database or network operations to finish before proceeding to the next

 #### Document the following Vocabulary Terms
#### Term
- Router Middleware

- Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router().

      var router = express.Router()
Dynamic Module Loading

- Singleton Pattern
- In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system
- CRUD -> REST Method Matches
- Mock Testing
- Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules

