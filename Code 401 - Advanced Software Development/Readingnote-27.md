[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-27 Props and State


### Review, Research, and Discussion

1- Does a deployed React application require a server?
   - You don't necessarily need a static server in order to run a Create React App project in production. It also works well when integrated into an existing server side app.

2- Why do we prefer to test a React application at the behavior rather than the unit level?
  - behavior driven development, also referred to as BDD, Implementing testing in React involves utilizing a test runner which is the library . so to get the most efficient output .
3- What does npm run build do?
  - npm run build creates a build directory with a production build of your app. Set up your favorite HTTP server so that a visitor to your site is served index. html , and requests to static paths like /static/js/main.

4- Describe the actual composition / architecture of a React application

   - Unlike other UI libraries and frameworks, Reactjs doesn't enforce an architecture pattern. It is just a view that caters to the user interface. Just beneath the user interface lies a tree of several React components


   ### Document the following Vocabulary Terms

   - BDD
      - Behavioral Driven Development (BDD) is a software development approach that has evolved from TDD (Test Driven Development). In both development approaches, tests are written ahead of the code, but in BDD, tests are more user-focused and based on the system's behavior.

- Acceptance Tests
      - An acceptance test is a formal description of the behavior of a software product, generally expressed as an example or a usage scenario.

- mounting
    - Mounting is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). In a browser that would mean outputting a React Element into an actual DOM element (e.g. an HTML div or li element) in the DOM tree.

- build 
   - npm run build creates a build directory with a production build of your app. Inside the build/static directory will be your JavaScript and CSS files. Each filename inside of build/static will contain a unique hash of the file contents.