# State and Props

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

render

## What is the very first thing to happen in the lifecycle of React?

Mounting

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

1- constructer.
React Update. 
2- render.
2- ComponentDidMount.
4- component WillUnmount. 

## What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().
setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.
Here we use componentDidMount() to connect to the YouTube API and get videos when the components is rendered.

## React State Vs Props

### What types of things can you pass in the props?

any data type strings, function ,objects,etc 

### What is the big difference between props and state?

 state is internal and controlled by the component itself while props are external and controlled by whatever renders the componen

### When do we re-render our application?

### What are some examples of things that we could store in state?

A re-render can only be triggered if a component’s state has changed. The state can change from a props change, or from a direct setState change. The component gets the updated state and React decides if it should re-render the component.