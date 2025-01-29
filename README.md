# JavaScript Null Value Handling

This repository demonstrates a common error in JavaScript:  the unexpected behavior of arithmetic operations and function calls when encountering `null` values.

The `bug.js` file shows the original code without proper null handling, while `bugSolution.js` provides a corrected version that explicitly checks for and handles null inputs.

## Bug Description

In JavaScript, attempting arithmetic operations involving `null` values will result in `NaN` (Not a Number).  This can be difficult to debug, particularly in larger codebases. This example shows how failure to account for `null` inputs can yield unexpected outputs in a simple addition function.

## Solution

The solution involves adding an explicit check for `null` or `undefined` values before performing any arithmetic or other operations that may be sensitive to these values.  This can prevent unexpected errors and improve code robustness. Consider using additional error handling like throwing exceptions if the `null` values are truly invalid or should not have been passed to the function. 

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run each file to observe the different behavior.
