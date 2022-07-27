# What is a ‘Controlled Component’?

In most cases, we recommend using controlled components to implement forms. In a controlled
component, form data is handled by a React component. The alternative is uncontrolled 
components, where form data is handled by the DOM itself.

To write an uncontrolled component, instead of writing an event handler for every state
update, you can use a ref to get form values from the DOM.


# Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

The most basic way of working with forms in React is to use what are referred to as “uncontrolled” form inputs.

What this means is that React doesn’t track the input’s state. HTML input elements naturally keep 

track of their own state as part of the DOM, and so when the form is submitted we have to read the values

from the DOM elements themselves.

# How do we target what the user is entering if we have an event handler on an input field?

React js is one of the most popular JavaScript frameworks today. There are a lot of companies whose websites are built on React due to the framework’s unique features. 

React UI comprises several components. There are a lot of tasks that users can perform on a React user interface. Each component has different HTML elements where the user can click, hover or trigger any form of event.  

Event Handlers: Events are the signals sent when there is a change in the UI. Users may click hover drag the mouse or press any key to perform these events. To respond to these changes 

users can write event handler code. You need to keep these 2 points in mind while working with React events.

React events are named in the format of camelCase (onChange instead of onchange).

React event handlers are placed inside curly braces (onChange={handleSubmit} instead of onChange=”handleSubmit”).

# Why would we use a ternary operator?

The ternary operator in the react js works in the same way how it works in the Javascript. With the help of the ternary operator, we can display the contents on the basis of one condition where everything depends

on the condition true and false we can put the contents on the conditional basis. We can take an example of a ternary operator like we fetch data from server and data is empty then we can use a data check ternary operator

where if data is empty or server is returning empty date then display some static data so that it will look good instead of displaying an empty to end-users.

Syntax:

Below is a simple syntax for the ternary operator in the react js. In the below syntax the first, we have written the conditional expression. This expression returns any boolean value and execution of the html

code are depends on the success of it, it fails or simply the condition is false then the html code will not be displayed.


# Rewrite the following statement using a ternary statement:



if(x===y){
  console.log(true);
} else {
  console.log(false);
}





javasscrpt{
(x===y)? console.log(true) : console.log(false) ;
}

