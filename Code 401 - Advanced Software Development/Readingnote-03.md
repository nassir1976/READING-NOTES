
[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-03



### Express REST API
### Review, Research, and Discussion
1. Name 3 real world use cases where you’d want to change the request with custom middleware
- invalid data ( bad data,
- reformating the data so it works perfectly with the database
- when you request data from server by using query string or params.

2. True or false: The route handler is middleware?
   - What is the difference between a route handler and middleware function in ExpressJS?
### Route Handler
- As a generic term, a route handler is code that is looking for a request to a specific incoming URL such as /login and often a specific HTTP verb such as POST and has specific code for handling that precise URL and verb
### Middleware
- As generic terms, middleware is code that examines an incoming request and prepares it for further processing by other handlers or short circuits the processing (like when it discovered the user is not authenticated yet)

3. In what ways can a middleware function end the process and send data to the browser?
- Middleware functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.

4. At what point in the request lifecycle can you “inject” middleware?

### The generated server allows for 3 extension points to inject middleware in its middleware chain. These have to do with the lifecycle of a request.

- The first one is to add middleware all the way to the top of the middleware stack. To do this you add them in the setupGlobalMiddleware method. This middleware applies to everything in the go-swagger managed API.
- The second extension point allows for middleware to be injected right before actually handling a matched request. This excludes the swagger.json document from being affected by this middleware though. This extension point makes the middlewares execute right after routing but right before authentication, binding and validation.
- The third point allows you to set the middleware for existing handler by its route and HTTP method. It can be done in the configureAPI function by calling api.AddMiddlewareFor method.
5. What can cause express to error with “Request headers sent twice, cannot start a second response”

- When a POST request is sent to /api/route1 it will run every line in the callback. A Can't set headers after they are sent error message will be thrown because res.json() is called twice, meaning two responses are sent.
 ### Document the following Vocabulary Terms
#### Term
- Middleware
- Request Object
- Response Object
- Application Middleware
- Routing Middleware
- Test Driven Development
- Behavioral Testing