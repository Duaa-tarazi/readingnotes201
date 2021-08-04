# Passing Functions as Props

## React Docs - lists and keys

### What does .map() return?

In React, transforming arrays into lists of elements is nearly identical.

### If I want to loop through an array and display each value in JSX, how do I do that in React?

 we loop through the numbers array using the JavaScript map() function. We return a ``` <li> ``` element for each item. Finally, we assign the resulting array of elements to listItems:

``` const numbers = [1, 2, 3, 4, 5]; ```
``` const listItems = numbers.map((number) => ```
  ``` <li>{number}</li> ```
``` ); ```

We include the entire listItems array inside a``` <ul> ``` element, and render it to the DOM:
``` ReactDOM.render( ```
 ``` <ul>{listItems}</ul>, ```
  ``` document.getElementById('root') ```
 ``` ); ```

### Each list item needs a unique ____.

Key

### What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity: