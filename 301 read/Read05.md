# Thinking in React

## How would you break a mock into a component heirarchy?

- draw boxes around every component and subcomponent and give them all names .
- use "single responsibility principle" to decide what should to be its own component.


## What is the single responsibility principle and how does it apply to components?

a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

its mean build a version that takes your data model and renders the UI but has no interactivity.

## Once you have a static application, what do you need to add?

you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child

## What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.

- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

if it changed over time.