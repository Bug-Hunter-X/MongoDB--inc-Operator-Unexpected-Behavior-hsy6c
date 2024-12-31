# MongoDB $inc Operator Unexpected Behavior

This repository demonstrates an uncommon error related to the MongoDB `$inc` operator.  The `$inc` operator is used to increment or decrement numeric fields in MongoDB documents. However, incorrect usage can lead to unexpected outcomes. 

The `bug.js` file showcases an example of how improper decrementing can result in unexpected results or errors.

The `bugSolution.js` file shows the correct implementation.

## How to reproduce

1.  Ensure you have a MongoDB instance running.
2.  Create a collection called `counters`.
3.  Run the code in `bug.js`.
4.  Observe the unexpected results.