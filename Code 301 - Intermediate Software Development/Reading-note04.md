[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-4

Responsive Web Design and Regular Expressions
Regular expressions (regex) are an essential part of any programmer’s toolkit. They can be very handy when you need to identify, replace or modify text, words, patterns or characters.
Regular expressions (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern (i.e. a specific sequence of ASCII or unicode characters).

### A Complete Guide to Grid
- CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows
### Important Terminology
display

Defines the element as a grid container and establishes a new grid formatting context for its contents.

grid-template-columns

grid-template-rows

Defines the columns and rows of the grid with a space-separated list of values. The values represent the track size, and the space between them represents the grid line.

Values:
- can be a length, a percentage, or a fraction of the free space in the grid (using the fr unit) OR

- an arbitrary name of your choosing

grid-template-areas

- Defines a grid template by referencing the names of the grid areas which are specified with the grid-area property. Repeating the name of a grid area causes the content to span those cells. A period signifies an empty cell. The syntax itself provides a visualization of the structure of the grid.

Values:

- the name of a grid area specified with grid-area
- a period signifies an empty grid cell

none – no grid areas are defined

**grid-template**

column-gap

row-gap

grid-column-gap

grid-row-gap

justify-items

align-items

place-items

justify-content

align-content

place-content

grid-auto-columns

grid-auto-rows

grid-auto-flow

### grid
- A shorthand for setting all of the following properties in a single declaration: grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns, and grid-auto-flow (Note: You can only specify the explicit or the implicit grid properties in a single grid declaration).

Attribute:https://css-tricks.com/snippets/css/complete-guide-grid/#prop-display