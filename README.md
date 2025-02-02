# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript error caused by the language's loose typing system.  The code attempts to add a number and a string, but instead of performing numerical addition, JavaScript performs string concatenation.

## The Bug

The `bug.js` file contains a function that adds two arguments. However, when one argument is a number and the other is a string, the result is unexpected due to JavaScript's automatic type coercion.

## The Solution

The `bugSolution.js` file shows how to fix this issue by explicitly converting both arguments to numbers before performing the addition. This ensures that the addition operation is performed numerically, providing the expected result.

## How to reproduce the bug:

1. Clone this repository
2. Navigate to the repository directory.
3. Run the script `bug.js` using Node.js or your preferred JavaScript environment (e.g., `node bug.js`).
4. Observe that the output is `510`, which is the result of string concatenation.
5. Run `bugSolution.js` to see the correct numerical addition.