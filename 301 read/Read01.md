
# Introduction to React and Components

## What is a component?

![](https://www.techdiagonal.com/wp-content/uploads/2019/08/React-components-blog-image.jpg)

A component is an independent, reusable code block, which divides the UI into smaller pieces,
A component can have three different views − object-oriented view, conventional view, and process-related view.

## What are the charactistics of a component?

- Reusability
- Replaceable
- Not context specific
- Extensible
- Encapsulated
- Independent .

## What are the advantages of using component based architecture?

- Reduced time in market and the development cost by reusing existing components.

- Increased reliability with the reuse of the existing components.


## What is props short for?

React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

## How are props used in React?

Firstly, define an attribute and its value(data)
Then pass it to child component(s) by using Props
Finally, render the Props Data

## What is the flow of props?

uni-directional flow. (one way from parent to child)
Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.
![](https://www.techdiagonal.com/wp-content/uploads/2019/09/react-props-blog-image-design-2.jpg)