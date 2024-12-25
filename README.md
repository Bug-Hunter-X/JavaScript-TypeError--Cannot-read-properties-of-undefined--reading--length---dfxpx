# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution. The bug arises from attempting to access the 'length' property of an undefined variable, even when a null check is in place.

## The Bug
The original code attempts to handle null values gracefully but fails to account for undefined values. This leads to a `TypeError` when an undefined variable is passed to the function.

## The Solution
The solution involves checking for both `null` and `undefined` using the strict equality operator (`===`) before attempting to access the 'length' property.