[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-31  Hooks API

### Review, Research, and Discussion

1- Why do we not need more .html pages in a multi-page React app?
   - we don't need more html pages in a multi page react app becouse we are able to use a browser router to rendor specific components on different paths. This has to do with how React renders to do the DOM.

  - To build a website with multiple routes instead of multiple pages. Because React is not designed to develop multi-page websites. So, we need to create multiple routes to handle multiple views.

  - create-react-app provides a great starting point to start a new react app fully configured with **webpack, live reloading, etc.** But, sadly, it doesn't provide a way to provide different index.html pages with a different set of entry points.

2- If we wanted a component to show up on every page, where would we put it and why?
  - Outside the <BrowserRouter/>
  - Inside the <BrowserRouter />, outside a <Route />
  - inside a <Route />
- to rendered a components to show up on every page we have to put it in the **browserRouter**  but it shoud  be **outside** of specific **Route** 

3- What does props.children contain?
  - props. children is used to display any data  between the opening and closing tags when invoking a component. 

### Document the following Vocabulary Terms

- Composition
   - React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.

- Children / Child Components
   - Children allow you to pass components as data to other components, just like any other prop you use. ... The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children
- Hash Routing
   - Hash-based routing. What we meant by hash-based routing is using the anchor part of the URL to simulate different content. For example http://site.com/#/products/list leads to displaying a list of products. We have to mention that the #/products/list bit is never sent to the server.

- Link Routing
   - link routing is utilizes a link or navlink tag to direct a user to another part of the page .