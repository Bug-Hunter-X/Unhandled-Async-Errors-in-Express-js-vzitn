# Unhandled Async Errors in Express.js
This repository demonstrates an example of unhandled asynchronous errors in an Express.js application and how to solve it.

## The Bug
The `bug.js` file shows an Express.js application with an asynchronous operation that might throw an error.  The error handling is incomplete, leading to application crashes when the asynchronous operation fails.

## The Solution
The `bugSolution.js` file demonstrates a corrected version that properly handles asynchronous errors, preventing application crashes.

## How to reproduce
1. Clone this repository
2. Navigate to the directory in the terminal
3. Run `node bug.js` (This will likely crash). 
4. Run `node bugSolution.js` (This will handle the error gracefully)
