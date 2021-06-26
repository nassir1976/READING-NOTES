[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-38 Redux - Asynchronous Actions

### Review, Research, and Discussion

1-How granular should your reducers be?

  - single responsiblity can be benficial for reducers, however, there are times when granularity is beneficial . it depends on how many aspect of state need to be changed in a given action 
   source: https://reactkungfu.com/2016/11/how-granular-are-your-redux-actions/

2-Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
  -  having multiple reducers fire for a commonly mentioned action can be benieficial to help in dry code and also create a confusion and bugs not hundled correctly.

3-Name a strategy for preventing the above

  -  TO preventing the above you can use thunk middleware to create a sequence of dispatching so that the state is not altered twice at the same time.

### Document the following Vocabulary Terms
### Term
- store
    - A store is basically just a plain JavaScript object that allows components to share state. In a way, we can think of a store as a database. On the most fundamental level, both constructs allow us to store data in some form or another.

- combined reducers
   - The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore .