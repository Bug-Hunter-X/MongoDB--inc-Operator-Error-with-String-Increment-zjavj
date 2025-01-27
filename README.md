# MongoDB $inc Operator Error with String Increment
This example demonstrates an incorrect usage of MongoDB's `$inc` operator, where a string is provided for incrementing a numeric field. This results in an error because `$inc` expects a numeric value.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.

## How to reproduce the error
1. Set up a MongoDB instance.
2. Create a collection.
3. Run the code in `bug.js`.
4. Observe the error message.