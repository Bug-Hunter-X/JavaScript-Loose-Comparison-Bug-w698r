# JavaScript Loose Comparison Bug

This repository demonstrates a common JavaScript bug caused by the loose comparison operator (`==`). Loose comparison can lead to unexpected behavior when comparing values of different types. This example shows how to use the strict equality operator (`===`) to avoid these issues.

## Bug
The `bug.js` file contains a function that demonstrates the problem. The function uses loose comparison to check for null values. This can lead to unexpected results, as demonstrated in the code.

## Solution
The `bugSolution.js` file shows the corrected version of the function.  It uses strict equality to correctly check for null values, avoiding the unexpected behavior.

## How to reproduce
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred code editor.
3. Run the code in a JavaScript environment and observe the differences in behavior.