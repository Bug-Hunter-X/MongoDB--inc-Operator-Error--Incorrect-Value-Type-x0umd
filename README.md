# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number results in unexpected behavior.

## Bug Description
The bug arises from passing a string value ("1") to the `$inc` operator instead of a number (1). This leads to the operator failing to increment the field correctly.

## Solution
The solution involves correcting the value passed to `$inc` to be a number, as shown in `bugSolution.js`.