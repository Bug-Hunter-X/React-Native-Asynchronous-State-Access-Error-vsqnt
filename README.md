# React Native Asynchronous State Access Error

This repository demonstrates a common error in React Native: attempting to access a state variable before it's been initialized, usually due to asynchronous operations.

## Problem
The `bug.js` file shows an example of fetching data asynchronously. The component tries to render and display data before the asynchronous operation completes, causing an error because `data` is initially `undefined`.

## Solution
The `bugSolution.js` file provides a corrected version using optional chaining and a loading state to handle the asynchronous nature of the data retrieval.  This prevents the error and improves user experience.