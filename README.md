# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The provided code attempts to populate an array, but due to an incorrect loop condition, it throws an `ArrayIndexOutOfBoundsException`. The corrected code shows how to prevent this error.

**Bug:** The buggy code iterates one element beyond the array's bounds.
**Solution:** The solution corrects the loop condition to iterate correctly up to the array's last index.