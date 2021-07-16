[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-41 React Native

### Review, Research, and Discussion

1- Compare and Contrast Redux Toolkit with Redux “Ducks”

- Redux Toolkit, an officially recommended and a SOPE library that stands for Simple, Opinionated, Powerful, and Effective state management library. It allows us to write more efficient code, speed up the development process, and automatically apply the best-recommended practices. It was mainly created to solve the THREE MAJOR ISSUES with Redux:

  - Configuring a Redux store is too complicated
  - Have to add a lot of packages to build a large scale application
  - Redux requires too much boilerplate code which makes it cumbersome to write efficient and clean code.


- Ducks is a modular pattern that collocates actions, action types and reducers.
According to the Ducks proposal:
A module…
1. MUST export default a function called reducer()
2. MUST export its action creators as functions
3. MUST have action types in the form npm-module-or-app/reducer/ACTION_TYPE
4. MAY export its action types as UPPER_SNAKE_CASE, if an external reducer needs to listen for them, or if it is a published reusable library

 [source](https://medium.com/@matthew.holman/what-is-redux-ducks-46bcb1ad04b7)

2- What is the principle advantage of Redux Toolkit

- Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience.


### Document the following Vocabulary Terms
### Term
- redux toolkit slices
   - A function that accepts an initial state, an object full of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state. This API is the standard approach for writing Redux logic.
- namespace
     - ReactJS components with namespace. Imagine we want a pattern where the children components can be composed in any order. But the children components cannot be used unless they exists in a very specific parent component. We can apply a name-spaced pattern to achieve this desire