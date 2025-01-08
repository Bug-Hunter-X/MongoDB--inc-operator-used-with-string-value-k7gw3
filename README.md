# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB: attempting to increment a field by a non-numeric value.  The provided `bug.js` file shows the incorrect implementation, while `bugSolution.js` offers the corrected version.

## Bug Description

The bug arises from using the `$inc` operator with a string value instead of a number. MongoDB's `$inc` operator expects a numeric value to increment the field by. Attempting to increment with a string will result in an error.

## Solution

The solution involves ensuring that the value passed to the `$inc` operator is a valid number. The corrected code in `bugSolution.js` demonstrates the correct usage.