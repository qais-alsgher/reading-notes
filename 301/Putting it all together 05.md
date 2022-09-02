# Putting it all together

# What is the single responsibility principle and how does it apply to components?

The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function

in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

All of that module, class or function's services should be narrowly aligned with that responsibility

# What does it mean to build a ‘static’ version of your application?

The static keyword defines a static method or property for a class, or a class static initialization block (see the link for more information about this usage).
Neither static methods nor static properties can be called on instances of the class. Instead, they're called on the class itself.

Static methods are often utility functions, such as functions to create or clone objects, whereas static properties are useful 
for caches, fixed-configuration, or any other data you don't need to be replicated across instances.

# Once you have a static application, what do you need to add?

Syntax
static methodName() { /* … */ }
static propertyName [= value];

// Class static initialization block
static {

}

### Examples
Using static members in classes

class Triple {
  static customName = 'Tripler';
  static description = 'I triple any number you provide';
  static calculate(n = 1) {
    return n * 3;
  }
}

class SquaredTriple extends Triple {
  static longDescription;
  static description = 'I square the triple of any number you provide';
  static calculate(n) {
    return super.calculate(n) * super.calculate(n);
  }
}

# What are the three questions you can ask to determine if something is state?

1.Can  accessible directly using the this when it in class constructor and other methods?
2. how calling static members from another static method?
3. define static methods by static keyword or class?


# How can you identify where state needs to live?

dentify every component that renders something based on that state.

Find a common owner component (a single component above all the components that need the state in the hierarchy).

Either the common owner or another component higher up in the hierarchy should own the state.

If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and 

add it somewhere in the hierarchy above the common owner component.

# What is a “higher-order function”?

higher-order component is a function that takes a component and returns a new component.



Without Higher-order function

javascript{
const persons = [
  { name: 'Peter', age: 16 },
  { name: 'Mark', age: 18 },
  { name: 'John', age: 27 },
  { name: 'Jane', age: 14 },
  { name: 'Tony', age: 24},
];
const fullAge = [];
for(let i = 0; i < persons.length; i++) {
  if(persons[i].age == 18) {
    fullAge.push(persons[i]);
  }
}
console.log(fullAge);
}
javascript{
With Higher-order function filter

const persons = [
  { name: 'Peter', age: 16 },
  { name: 'Mark', age: 18 },
  { name: 'John', age: 27 },
  { name: 'Jane', age: 14 },
  { name: 'Tony', age: 24},
];
const fullAge = persons.filter(person => person.age == 18);
console.log(fullAge);

}

This function applies to all element in array and compare the equal for arrow function
and return the value of  equal is true  and stored in array

# Explain how either map or reduce operates, with regards to higher-order functions.
## map
Use map to loop over a collection and apply the same operation to each element in the collection. The map function
returns an array containing the results of applying a mapping or transform function to each item.

## regards
The reduce method executes the callback function on each member of the calling array which results in a single output value.
The reduce method accepts two parameters: 1) The reducer function (callback), 2) and an optional initialValue.


