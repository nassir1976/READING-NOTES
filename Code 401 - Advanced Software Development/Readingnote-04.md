
[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-04

### Readings: Data Modeling
1- Name 3 advantages to Test Driven Development

- Better program design and higher code quality. ...
- Detailed project documentation. ...
- TDD reduces the time required for project development. ...
- Code flexibility and easier maintenance. ...
- With TDD you will get a reliable solution. ...
- Save project costs in the long run.
2- In what case would you need to use beforeEach() or afterEach() in a test suite?

- The difference is beforeEach()/afterEach() automatically run before and after each tests, which 1. removes the explicit calls from the tests themselves, and 2. invites inexperienced users to share state between tests. Tests should be explicit, and tests should never share state. So why use tools that introduce magic (making it harder to understand a particular test) and invite test coupling?
3- What is one downside of Test Driven Development

- Big time investment. For the simple case you lose about 20% of the actual implementation, but for complicated cases you lose much more.
- Additional Complexity. For complex cases your test cases are harder to calculate, I'd suggest in cases like that to try and use automatic reference code that will run in parallel in the debug version / test run, instead of the unit test of simplest cases.
- Design Impacts. Sometimes the design is not clear at the start and evolves as you go along - this will force you to redo your test which will generate a big time lose. I would suggest postponing unit tests in this case until you have some grasp of the design in mind.
- Continuous Tweaking. For data structures and black box algorithms unit tests would be perfect, but for algorithms that tend to be changed, tweaked or fine tuned, this can cause a big time investment that one might claim is not justified. So use it when you think it actually fits the system and don't force the design to fit to TDD.
4- What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

- Instances are typically instantiated via constructor functions with the new keyword. Class inheritance may or may not use the class keyword from ES6. Classes as you may know them from languages like Java don’t technically exist in JavaScript. Constructor functions are used, instead. The ES6 class keyword desugars to a constructor function:
5- Why REST?

### REpresentational State Transfer
- REST, or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant systems, often called RESTful systems, are characterized by how they are stateless and separate the concerns of client and server. We will go into what these terms mean and why they are beneficial characteristics for services on the Web.

- In the REST architectural style, the implementation of the client and the implementation of the server can be done independently without each knowing about the other. This means that the code on the client side can be changed at any time without affecting the operation of the server, and the code on the server side can be changed without affecting the operation of the client.

### Document the following Vocabulary Terms
 #### Term
- functional programming
- object-oriented programming (OOP)
- class -- Classes are a template for creating objects.
- super --The super keyword refers to the parent class.
- this - The JavaScript this keyword refers to the object it belongs to.
- Test Driven Development (TDD)
- Jest - Jest is a delightful JavaScript Testing Framework with a focus on simplicity.
- Continuous Integration (CI)
- REST - REpresentational State Transfer
- Data Model - A data model refers to the logical inter-relationships and data flow between different data elements involved in the information world. It also documents the way data is stored and retrieved. ... Data models help represent what data is required and what format is to be used for different business processes

- source:https://medium.com/ 

- https://stackoverflow.com/questions/64333/disadvantages-of-test-driven-development