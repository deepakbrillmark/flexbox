## container
- display: flex; /* or inline-flex */
- flex-direction: row | row-reverse | column | column-reverse;
- flex-wrap: nowrap | wrap | wrap-reverse;
- flex-flow: <‘flex-direction’> || <‘flex-wrap’>
- justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
- align-items: stretch | flex-start | flex-end | center | baseline;
- align-content: flex-start | flex-end | center | space-between | space-around | stretch;

## item
- order: <integer>;
- flex-grow: <number>;
- flex-shrink: <number>; 
- flex-basis: <length> | auto;
- flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
- align-self: auto | flex-start | flex-end | center | baseline | stretch;
  
