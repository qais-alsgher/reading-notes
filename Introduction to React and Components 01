# Component
A component is a functionally independent part of any system. 
It performs some function and may require some input or produce some 
output. A component in software is often represented by classes.

# Component characteristics

The Characteristics tab is visible for concrete components.

Characteristics describe a component and must be used in combination with capabilities.


# Component-Based Architecture

Component-Based Architecture is a branch of software engineering which provides a higher level of abstraction than object-oriented design principles.

Component-Based architecture does not focus on issues such as communication protocol and shared state.

This architecture focuses on the decomposition of the design into logical components which contain events, methods and properties.

Component-Based architecture divides the problem into sub-problems and each problem associated with component partitions.

It provides a higher level of abstraction than object-oriented design principles.

It does not focus on issues such as communication protocols and shared state.

![](https://www.tutorialride.com/images/software-architecture-and-design/principles-of-component-based-architecture.jpg)

# Props
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. 
But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child).

# How to use props in React
In this section, you will learn two ways to use props: one without destructuring and the other with destructuring.


### How to use props without destructuring
To use props, you have to pass in props as an argument in your function. This is similar to passing 
arguments into your regular JavaScript functions. Here's an example:

function Tool(props) {
  const name = props.name;
  const tool = props.tool;
    return (
      <div>
        <h1>My name is {name}.</h1>
        <p>My favorite design tool is {tool}.</p>
      </div>
    );
}

### How to set default values for props
If you do not want your props data to be empty when you create them, you can pass in a default value. Here's how to do that:

function Tool({name, tool}) {

    return (
      <div>
        <h1>My name is {name}.</h1>
        <p>My favorite design tool is {tool}.</p>
      </div>
    );

  }
  
  Tool.defaultProps = {
    name: "Designer",
    tool: "Adobe XD"
  }

# What is the flow of props?
Data between Components
Every component is part of the component tree typically with your App component at the top. Any components that App renders in its JSX are its children and so forth. A component 
can't receive data from its siblings or children so how would data move around, here are some scenarios.

To Child From Parent
The Parent passes the data to its child as a prop

To Parent from Child
Parents have state to hold the data and sends the child the setState function nested in another function. The child then passes the data to this function to update the state in the parent.

From Sibling to Sibling
Since siblings can't send data to each other trick is to use a shared parent (this is also known as lifting state.)

For the Sibling Sending Data: In the shared parent state is created to hold the information and a function to set that state is passed down as props to the sending component.

For the Sibling Receiving Data: Once the shared parents' state has been updated the parent passes down that state as props to the receiving component.


