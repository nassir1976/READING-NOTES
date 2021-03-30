[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-3

MUSTACHE and FLEXBOX
 ### JavaScript Templating
- JavaScript templating refers to the client side data binding method implemented with the JavaScript language. This approach became popular thanks to JavaScript's increased use, its increase in client processing capabilities, and the trend to outsource computations to the client's web browser. ... js, Vue. js and Mustache.
 ### JavaScript Templating: What is Templating?
- JavaScript templates take simple web apps to the next level, keeping your application logic separate from your presentation and your HTML and JS files clean
 ### Template Engine
The template engine is responsible for:

- connecting to the data model;
- processing the code specified in the source templates; and
- directing the output to a specific pipeline, text file, or stream.
 ### Mustache
                       {{ mustache }}
- Mustache is a logic-less template syntax. It can be used for HTML, config files, source code - anything. It works by expanding tags in a template using values provided in a hash or object

- mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

 ### Where to use mustache.js?
- You can use mustache.js to render mustache templates anywhere you can use JavaScript. This includes web browsers, server-side environments such as Node.js, and CouchDB views.

- mustache.js ships with support for the CommonJS module API, the Asynchronous Module Definition API (AMD) and ECMAScript modules.

 ### A Complete Guide to Flexbox
- Flexbox is a one-dimensional layout method for laying out items in rows or columns. Items flex to fill additional space and shrink to fit into smaller spaces.
- Why Flexbox? For a long time, the only reliable cross browser-compatible tools available for creating CSS layouts were things like floats and positioning. These are fine, and they work, but in some ways they are also rather limiting and frustrating.

#### The following simple layout requirements are either difficult or impossible to achieve with such tools, in any kind of convenient, flexible way:

- Vertically centering a block of content inside its parent.

- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

- The flex model When elements are laid out as flex items, they are laid out along two axes.

 ### Properties for the Parent
(flex container)

- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-content
 ### Properties for the Children
(flex items)

- order
- flex-grow
- flex-shrink
- flex-basis
- flex
- align-self

attribution : https://medium.com/@1sherlynn/javascript-templating-language-and-engine-mustache-js-with-node-and-express 

https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox