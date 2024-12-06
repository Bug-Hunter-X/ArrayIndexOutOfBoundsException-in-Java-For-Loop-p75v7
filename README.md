# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The error occurs when attempting to access an array element using an index that is outside the valid range of indices for the array.  Valid indices range from 0 to array.length - 1.

The `bug.java` file contains code that produces this exception. The `BugSolution.java` file shows the corrected code.

## How to reproduce
1. Clone this repository
2. Compile and run `bug.java`
3. Observe the `ArrayIndexOutOfBoundsException`
4. Examine `BugSolution.java` to see how to fix the issue.

## Learning Outcome
This example helps to understand the importance of carefully managing array indices in Java loops and avoiding off-by-one errors, a frequent source of runtime exceptions.