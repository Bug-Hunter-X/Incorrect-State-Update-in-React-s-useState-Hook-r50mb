# Incorrect State Update in React's useState Hook

This example demonstrates a common error when using React's `useState` hook. The code attempts to directly modify the state variable, which is incorrect.  React's `useState` requires the use of the setter function provided by the hook to update values.

## Bug
The `bug.js` file contains code with incorrect state update. The `count` variable in `MyComponent` attempts to update directly leading to unexpected behavior (no re-render). 

## Solution
The `bugSolution.js` shows the correct way to update state using the `setCount` function.