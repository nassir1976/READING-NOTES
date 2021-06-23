[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-37 Redux - Combined Reducers

### Review, Research, and Discussion

1- Why choose Redux instead of the Context API for global 
state?
  - For  more complex state which has high-frequency updates, the React Context won't be a good solution. Because, the React Context will trigger a re-render on each update, and optimizing it manually can be really tough. And there, a solution like Redux is much easier to implement.
2- What is the purpose of a reducer?
  - A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

3- What does an action contain?
  - An action, is an object that contains the payload of information. They are the only source of information for the Redux store to be updated. Reducers update store based on the value of the action. type

4- Why do we need to copy the state in a reducer?
   - If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.

####  Document the following Vocabulary Terms
### Term
- immutable state
     - Immutability is a concept that React programmers need to understand. An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched.

- time travel in redux
    - Time travel debugging refers to the ability step forward and backward through the state of you application, empowering the developer understand exactly what is happening at any point in the app's lifecycle

- action creator

   - An action creator is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.

- reducer

- In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action.

- dispatch

  - dispatch is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you.