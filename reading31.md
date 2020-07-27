## hooks 
- https://reactjs.org/docs/hooks-overview.html
- here, useState is a Hook (we’ll talk about what this means in a moment). We call it inside a function component to add some local state to it
- The array destructuring syntax lets us give different names to the state variables we declared by calling useState. These names aren’t a part of the useState API. 
- Instead, React assumes that if you call useState many times, you do it in the same order during every render. We’ll come back to why this works and when this is useful later.

- he Effect Hook, useEffect, adds the ability to perform side effects from a function component. 
- It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount

## Rules of Hooks
#### Hooks are JavaScript functions, but they impose two additional rules:
- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.



## state hook
- https://reactjs.org/docs/hooks-state.html


## effects hook
- https://reactjs.org/docs/hooks-effect.html

## hooks api reference
- https://reactjs.org/docs/hooks-reference.html

## Lists and Keys
- https://reactjs.org/docs/lists-and-keys.html

## Forms
- https://reactjs.org/docs/forms.html