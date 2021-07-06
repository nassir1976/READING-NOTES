[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-39 Redux - Additional Topics

### Review, Research, and Discussion

1- What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
 - The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.
2- When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
 
 we are exporting a function from the reducer/ action creator
### Document the following Vocabulary Terms
### Term
- middleware
  - Middleware is software that is used to bridge the gap between applications and other tools or databases. Middleware sits between an operating system and the applications that run on it. It is effectively software that provides a method of communication and data management between applications that would otherwise not have any way to exchange data -- such as with software tools and databases.
- thunk
    - Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. One of the main use cases for this middleware is for handling actions that might not be synchronous, for example, using axios to send a GET request.