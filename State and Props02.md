
# Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
 The render() because method is required and will always be called, the others are optional and will be called if you define them.
 and he componentDidMount() method is called after the component is rendered.
 
 # What is the big difference between props and state?
 
 ### PROPS
 1.The Data is passed from one component to another.
 2.It is Immutable (cannot be modified).
 3.Props can be used with state and functional components.
 4.Props are read-only.
 
 ### STATE
 1.The Data is passed within the component only.
 2.t is Mutable ( can be modified).
 3.State can be used only with the state components/class component (Before 16.0).
 4.	State is both read and write.



# When do we re-render our application?

When looking into React's render performance, there are a few terms and concepts that can be hard to understand.

It wasn't 100% clear to me what a VDOM was or how React decides to re-render components for quite some time.

In the first part of this article, I'll explain the most important concepts about rendering in React and how React decides to re-render a given component.


and every thing in lifecycle of React

A component’s lifecycle is broadly classified into four parts:

initialization 

mounting

updating, and

unmounting.

# What are some examples of things that we could store in state?

When React was first introduced, we were presented with local state. The important thing to know about local 
state is that when a state value changes, it triggers a re-render.


