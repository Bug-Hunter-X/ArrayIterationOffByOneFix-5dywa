# Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The bug involves incorrectly accessing an array element beyond its valid index range.

The `Bug.java` file contains the code exhibiting the error. The `BugSolution.java` file presents the corrected code.

## Bug
The bug is located in the `for` loop within the `main` method. The loop condition `i <= arr.length` causes the loop to iterate one time too many, leading to an `ArrayIndexOutOfBoundsException`.