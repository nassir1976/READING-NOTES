[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-33 Context API

#### REVIEW, RESEARCH AND DISCUSS

1- Describe use cases for useMemo() and useReducer()
  
  - The useMemo is a hook used in the functional component of react that returns a memoized value. ... In react also, we use this concept, whenever in the React component, the state and props do not change the component and the component does not re-render, it shows the same output.

  - useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.


2- Why do custom hooks need the use prefix?
  
  - The name of any custom hook should begin with **use**. this convention indicates to developers that hooks are used within the file/custom hook 

3- What do custom hooks usually do?

 - Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated. How does a custom Hook get isolated state? Each call to a Hook gets isolated state

4- Using any list of custom hooks, research and name one that you think will be useful in your applications
  - the UseArray hooks looks particularly helpful b/s arry manipulation is common in javascript.

5- Describe how a hook that fetches API data might work
  
  - Get the free API fetch Data with useEffect  

   - State variable is ready to store the response data.
   - API call happens when the component is mounted
   - Response data is saved to the state variable
### Document the following Vocabulary Terms
### Term

- reducer

   - A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. more complex items than use state can able handle 