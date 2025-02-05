# PHP Type Error in Array Summation
This repository demonstrates a common error in PHP related to type juggling when performing arithmetic operations on arrays containing mixed data types.
The `calculateSum` function intends to calculate the sum of numbers in an array. However, it fails when encountering a string value within the array because PHP attempts to implicitly convert the string to a number which can lead to unexpected results.
The solution provides improved type handling to prevent this error.  The solution demonstrates how to handle type errors gracefully, ensuring the function correctly sums only numeric values, thus preventing unexpected behavior.