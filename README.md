# React Native: Handling undefined state variables

This repository demonstrates a common error in React Native: accessing state variables or props before they've been assigned a value. This often happens with asynchronous operations or when a component renders before receiving necessary data.

The `bug.js` file shows the incorrect code that throws the error 'Cannot read properties of undefined (reading 'someProperty')'.  The `bugSolution.js` file shows the correct solution using optional chaining and/or nullish coalescing.