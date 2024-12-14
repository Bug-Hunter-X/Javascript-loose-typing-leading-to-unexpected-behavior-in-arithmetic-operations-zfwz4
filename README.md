# Javascript Loose Typing Leading to Unexpected Behavior in Arithmetic Operations
This example demonstrates how Javascript's loose type system can lead to unexpected behavior when performing arithmetic operations on different data types.  The bug showcases string concatenation instead of numerical addition when mixing number and string operands.
The solution provides a method to explicitly type-check and handle the inputs to ensure correct arithmetic operations.
## Bug
The primary bug is that Javascript implicitly converts numbers to strings when using the + operator with a string, leading to unexpected string concatenation rather than addition.
## Solution
The solution involves adding explicit type checking before performing addition. This ensures that only numbers are added, preventing unexpected string concatenation.
