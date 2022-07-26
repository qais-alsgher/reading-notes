# Passing Functions as Props

# What does .map() return?
he map() method in JavaScript creates an array by calling a specific function on each element present in the parent array.
It is a non-mutating method. 

#If I want to loop through an array and display each value in JSX, how do I do that in React?
I used the map() because method is used to iterate over an array and calling function on every element of array.

# Each list item needs a unique "key".

# What is the spread operator?

The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements.

The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.

# List 4 things that the spread operator can do.
1.pread syntax (...) allows an iterable, such as an array or string, to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected.
In an object literal, the spread syntax enumerates the properties of an object and adds the key-value pairs to the object being created.

2.Replace apply()

3.splice()

4.Object.assign()

# Give an example of using the spread operator to combine two arrays

const arr1 = ["Cecilie", "Lone"];
const arr2 = ["Emil", "Tobias", "Linus"];
const children = arr1.concat(arr2);

# Give an example of using the spread operator to add a new item to an array.

const array = [1, 2, 3];
const obj = { ...array }; // { 0: 1, 1: 2, 2: 3 }

# Give an example of using the spread operator to combine two objects into one.

let person = {
    firstName: 'John',
    lastName: 'Doe',
    age: 25,
    ssn: '123-456-2356'
};


let job = {
    jobTitle: 'JavaScript Developer',
    location: 'USA'
};

let employee = {
    ...person,
    ...job
};

console.log(employee);
