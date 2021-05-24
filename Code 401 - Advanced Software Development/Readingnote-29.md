[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-29  Routing

### Review, Research, and Discussion 

1- Do child components have direct access to props/state from the parent?
 - There is no way to pass props from a child component to a parent component. However, we can always pass around functions from the parent to child component. The child component can then make use of these functions. The function can then update the state in a parent component.

2- When a component “wraps” another component, how does the child component’s output get rendered?

                  <Main>
                   <Content />
                   </Main>


 - Wrapper components are components that provide a default structure to ... The author selected Creative Commons to receive a donation as part of the ... Then you'll create a component that uses the built-in children component to wrap. 

3- Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
-  yes we can use a child components elsewhere on standalone in the application.

4-What trick can a parent use to share all props with it’s children

- Instead, to pass all React props from parent to child at once, you need to take advantage of the spread operator ( ... ). The spread operator lets you pass the entire props object to a child component as that child's props object.

### Document the following Vocabulary Terms

- props.children

- props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. A simple example: Here's an example of a stateless function that is used to create a component.

- composition.
  - React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.