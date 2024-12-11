# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `bug.java` file contains the erroneous code, which attempts to access an array element beyond its bounds. The `bugSolution.java` file provides the corrected code.

**Problem:** The original code's for loop iterates one element past the end of the array, resulting in an `ArrayIndexOutOfBoundsException`. 

**Solution:** The solution modifies the loop condition to correctly iterate up to (but not including) the array's length.