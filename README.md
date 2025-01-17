# MongoDB $inc Operator Error
This example demonstrates an uncommon error in MongoDB when using the `$inc` operator.  The error occurs when attempting to increment a field using a string value instead of a numerical value.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file demonstrates the correct usage.

To reproduce the error, ensure you have a MongoDB database set up, and a collection called 'myCollection' with at least one document containing a numerical field named 'count'.