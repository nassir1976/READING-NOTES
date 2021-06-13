[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-34 Login  and Auth 

### Review, Research, and Discussion

1- Why is the Context API useful?
  - The React Context API is a way for a React app to effectively produce global variables that can be passed around. This is the alternative to "prop drilling" or moving props from grandparent to child to parent, and so on.

2- Can a component outside of a provider get its context?
  - The context API works like a tree. The consumer component needs to be inside the tree. Therefore, the consumer will not work outside of the scope of the tree.

3- What are some common use cases for using the Context API?

- Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than contex
  - Themes. The ability to set the theme is one of the best use context API.
  - Multilingual application. To implement multiple languages in app we have to change the text in every component and replace with the translated text. 
  - Authorisation: setting the user role and info.

4- Describe “Context Hell”
  - Context Hell is like the callback hell, usual when jQuery was used for everything, the React Context hell is the nasty code you get taking advantage of the React Context API.


### Document the following Vocabulary Terms
### Term
- global state

   - global state is context provides a way to pass data through the component tree without having to pass props down manually at every level, managing state in multiple components that are not directly connected

- global context
  - Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language

- provider
  - React uses provider pattern in Context API to share data across the tree descendant nodes.

- consumer
  - A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component. ... The function receives the current context value and returns a React node.