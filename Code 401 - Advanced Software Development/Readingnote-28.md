[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-28 Component Composition

### Review, Research, and Discussion 


1- Can a parent component access the state of a child component?

 - In React we can access the child’s state using Refs.  we will assign a Refs for the child component in the parent component. then using Refs we can access the child’s state.

2- What can be passed along in a prop variable?

  - we can pass any data type, state, strings .

3- How can a child component “know” the state of another component?

- To be able to access and update state from the child component, we can add a method that handles updating the state to the parent component and pass the method as a prop to the child component instead of the state itself.


### Document the following Vocabulary Terms

- component props
    - Props are arguments passed into React components. Props are passed to components via HTML attributes.
- component state
    - The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

- application state

- An application state is simply the state at which an application resides with regards to where in a program is being executed and the memory that is stored for the application. The web is "stateless," meaning everytime you reload a page, no information remains from the previous version of the page.