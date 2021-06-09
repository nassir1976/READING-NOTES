[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-32 Custom  Hooks


#### REVIEW, RESEARCH AND DISCUSS

1- What does a component’s lifecycle refer to?
   - Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are:

mounting

updating

unmounting

2- Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect
  - useCallback will help in avoiding regeneration of functions when the functional component re-renders. However there isn’t much of a performance difference caused by recreation of functions.

3- Why are functional components preferred over class components?

  - Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks.also when the react app run its fast.


4- What is wrong with the following code?
           import React, {useState, useEffect} from 'react';

           function MyComponent(props) {
           const [count, setCount] = useState(0);

          function changeCount(e) {
          setCount(e.target.value);
          }

          let renderedItems = []

         for (let i = 0; i < count; i++) {
         useEffect( () => {
          console.log('component mount/update');
         }, [count]);

         renderedItems.push(<div key={i}>Item</div>);
        }

          return (<div>
          <input type='number' value={count} onChange={changeCount}/>
        {renderedItems}
       </div>);
       }

- the  loop it will cause infinite re-render .


TERMS:
### state hook
  - A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.
   - Example  useState() allows you to use state and other React features without writing a class. Hooks are the functions which “hook into” React state and lifecycle features from function components.

### effect hook
  - The Effect Hook lets you perform side effects in function components: import React, { useState, useEffect } from 'react'; function Example() { const [count, setCount] = useState(0); // Similar to componentDidMount and componentDidUpdate: useEffect(() => { // Update the document title using the browser API document.
 
### reducer hook
 - useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.

