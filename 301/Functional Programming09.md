# Functional Programming

What is functional programming?

unctional programming is a programming paradigm where programs are constructed by applying and 

composing functions. It is a declarative programming paradigm in which function definitions are trees 

of expressions that map values to other values, rather than a sequence of imperative statements which

update the running state of the program.

# What is a pure function and how do we know if something is a pure function?

Given the same input, always returns the same output.

Produces no side effects.

# What are the benefits of a pure function?
1. Readability

Pure functions are much easier to read and reason about.

All relevant inputs and dependencies are provided as parameters,

so no effects are observed that alter variables outside of the set of inputs.

2.Portability

As all dependencies are provided as input parameters and are not accessed through 

a global context, these dependencies can be swapped out depending on the context in which the function is called.

3.Caching

As pure functions always return the same output for the same input, we can cache the results of pure function calls.

Caching refers to using a technique, such as memoization, to store the results of functions so that we only need to calculate them once.



# What is immutability?

object-oriented and functional programming, an immutable object (unchangeable object) is an object whose state cannot

be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after 

it is created. In some cases, an object is considered immutable even if some internally used attributes change, but the 

object's state appears unchanging from an external point of view. For example, an object that uses memoization to cache the 

results of expensive computations could still be considered an immutable object.

# What is Referential transparency?

eferential transparency and referential opacity are properties of parts of computer programs. An expression is called 

referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program's

behavior.This requires that the expression be pure – its value must be the same for the same inputs and its evaluation must have

no side effects. An expression that is not referentially transparent is called referentially opaque.

# What is a module?

 module is a distinct assembly of components that can be easily added, removed or replaced in a larger system. Generally, a module 
 
 is not functional on its own. In computer hardware, a module is a component that is designed for easy replacement.
 
 In computer software, a module is an extension to a main program dedicated to a specific function. In programming,
 
 a module is a section of code that is added in as a whole or is designed for easy reusability.
 
 # What does the word ‘require’ do?
 
 require() method is used to load and cache JavaScript modules. So, if you want to load a local,
 
 relative JavaScript module into a Node. js application, you can simply use the require() method
 
 # How do we bring another module into the file the we are working in?
 
 module.exports = (whatever needed);
 or
 module.exports.function need;
 
 
 # What do we have to do to make a module available?
 
 module.exports = {whatever need available}

 

