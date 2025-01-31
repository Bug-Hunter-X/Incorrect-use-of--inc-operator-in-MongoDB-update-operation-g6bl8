# MongoDB $inc Operator Error
This example demonstrates an uncommon error in MongoDB when using the `$inc` operator to increment a numeric field.  The error arises from providing a string value instead of a numeric value to the `$inc` operator resulting in string concatenation instead of numerical increment.

## Bug
The original code uses the `$inc` operator with a string value which causes unexpected string concatenation. 

## Solution
The solution uses a numeric value with the `$inc` operator which corrects the increment operation, thereby avoiding string concatenation. 
