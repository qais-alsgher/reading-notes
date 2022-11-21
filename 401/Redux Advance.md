# Redux Advance

### Redux 

is an open-source JavaScript library for managing application state. It is most commonly used with libraries such as React or

Angular for building user interfaces.

### Redux Toolkit 

was introduced with a purpose to be the standard way to write redux logic. It is said to be an opinionated, batteries-included 

toolset for efficient Redux development. By using this, you can write all the code you need for your Redux store in a single file, including actions

and reducers. Using this you can make your code more readable. Redux toolkit includes all the tools, you want for a Redux application. At the end of the

day all you have is less code and faster setups of Redux in every scenario.



## What's Included

### Redux Toolkit includes:

configureStore(): wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers,

adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

createReducer(): that lets you supply a lookup table of action types to case reducer functions, rather than writing switch statements. In addition,

it automatically uses the immer library to let you write simpler immutable updates with normal mutative code, like state.todos[3].completed = true.

createAction(): generates an action creator function for the given action type string. The function itself has toString() defined, so that it can be 

used in place of the type constant.

createSlice(): accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with

corresponding action creators and action types.

createAsyncThunk: accepts an action type string and a function that returns a promise, and generates a thunk that dispatches pending/fulfilled/rejected 

action types based on that promise

createEntityAdapter: generates a set of reusable reducers and selectors to manage normalized data in the store

The createSelector utility from the Reselect library, re-exported for ease of use.



## What is createSlice in Redux Toolkit?

createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name.

It automatically generates action creators and action types that correspond to the reducers and state.


### For more information ([click here](https://github.com/qais-alsgher/reading-notes/blob/main/README.md))

### useful links 
[Redux Toolkit]([](https://redux.js.org/redux-toolkit/overview))



