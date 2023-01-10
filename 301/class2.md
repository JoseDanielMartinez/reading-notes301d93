# ***Overview***

Knowing the importance of React's lifecycle events pays dividends when you as the developer understand how to use components as classes or functions methods during differing cycles to update UI and application states.  It's a time saver versus it's predecessor; Hard coding objects.


## ***Class 2 Assignment***

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

The render.

2. What is the very first thing to happen in the lifecycle of React?

Mounting

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  
Constructor, render, React Updates, componentDidMount, componentWillMount

4. What does componentDidMount do?

This method is invoked immediately after a component is mounted.  If you need to load anything using a network request or initialize the DOM, it should go here.  This method is a good place to set up any subscriptions.

[Source:React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

 1. What types of things can you pass in the props?

 You can pass the initial components inside our props.  They are what we wanna use to pass things to a function.

 2. What is the big difference between props and state?

 Props we pass into a component and states are handled inside of the component.

 3. When do we re-render our application?

 When we change the state inside of our application it'll rerender.

 4. What are some examples of things that we could store in state?

 User information from a form or anything we want to update from within a component.

[Source: Web Dev Simpli](https://www.youtube.com/watch?v=IYvD9oBCuJI)

## Things I want to know more about
