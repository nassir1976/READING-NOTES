
[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-2

### JQUERY
- What is jQuery? jQuery is a lightweight, "write less, do more", JavaScript library.
The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

- The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities

 jQuery - Get and Set CSS Classes

jQuery has several methods for CSS manipulation. We will look at the following methods:

addClass() - Adds one or more classes to the selected elements

removeClass() - Removes one or more classes from the selected elements

toggleClass() - Toggles between adding/removing classes from the selected elements

css() - Sets or returns the style attribute

 ### WHY USE JQUERY?
- jQuery doesn't do anything you cannot achieve with pure JavaScript. It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler.

SIMPLE SELECTORS

COMMON TASKS IN LESS CODE

GETTING ELEMENT CONTENT

html() retrieve and update the content of elements

text() retrieve and update the content of elements

 ### jQuery Traversing
-jQuery traversing, which means "move through", are used to "find" (or select) HTML elements based on their relation to other elements. Start with one selection and move through that selection until you reach the elements you desire.

### Traversing the DOM
jQuery provides a variety of methods that allow us to traverse the DOM.

The largest category of traversal methods are tree-traversal.

The next chapters will show us how to travel up, down and sideways in the DOM tree.

### jQuery Traversing - Ancestors
With jQuery you can traverse up the DOM tree to find ancestors of an element.
### Traversing Up the DOM Tree
Three useful jQuery methods for traversing up the DOM tree are:

parent()
parents()
parents Until()
### Inserting new elements involves two steps:
Create the new elements in a jQuery object

                                                 example    <l i>element:var $newFragment = $('<li>'}
Use a method to insert the content into the page

.before()

.after()

.prepend()

.append()

Query allows you to recreate the functionality of a loop on a selection of elements, using the • each () method.

THE EVENT OBJECT

Every event handling function receives an event object. It has methods and properties related to the event that occurred.

### jQuery Animations - The animate() Method
The jQuery animate() method is used to create custom animations.

### PREVENTING CONFLICTS WITH OTHER LIBRARIES
$ () was shorthand for j Query ().The $ symbol is used by other libraries such as prototype.js, MooTools, and YUi. To avoid conflicts with those scripts, use these techniques.
### 6 Reasons for Pair Programming
- Greater efficiency
- Engaged collaboration
- Learning from fellow students
- Social skills
- Job interview readiness
- Work environment readiness

Attribution
- JavaScript and jQuery ( Jon Duckett book)
- https://www.w3schools.com/jquery/