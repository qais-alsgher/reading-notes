#  In memory storage

# What is a ‘call’?

A function call is an expression containing the function name followed by the function call operator, () 


# How many ‘calls’ can happen at once?

It is single-threaded. Meaning it can only do one thing at a time.


# What does LIFO mean?

LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, 

it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.


#  Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.


![image](https://user-images.githubusercontent.com/69685164/182743701-523db6ad-721c-493f-ab75-a115999c21be.png)



# What causes a Stack Overflow?

stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.


# What is a ‘reference error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

his is also a common thing when using const and let, they are hoisted like var and function but there is a 

time between the hoisting and being declared so when you try to access them a reference error occurs

# What is a ‘syntax error’?

 occurs when you have something that cannot be parsed in terms of syntax
 
 
 # What is a ‘range error’?
 
 Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

An array for instance cannot have a negative length, why would you mess with the array length? Some people use it to

set an array to empty, something of the likes 

# What is a ‘tyep error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to

use or access are incompatible, like accessing a property in an undefined type of variable.

The fix is simple, just make sure that bar exists before trying to access it, either by creating bar or by checking for undefined.

# What is a breakpoint?

Is to break the code into small parts to enable us to know the cause of the error.

example

You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point

only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. In this example the breakpoint will 

point stop when the index reaches 40.


# What does the word ‘debugger’ do in your code?

A debugger is a software tool that can help devloper to see the “history” before reaching that breakpoint












