# React Reducer

# How can we ensure that an effect hook runs only once?

pass an empty array as the second argument (dependancy) to the useEffect hook.

# Can useState() update more than one state variable at the same time?

No because side effect of which seems to be multiple re-renders when they are updated separately.

We can do it if have a dependancy for use useRucer hook

# Is useState() synchronous?

No useStateis an asynchronous hook and it doesn’t change the state immediately, it has to wait for the component to re-render.




