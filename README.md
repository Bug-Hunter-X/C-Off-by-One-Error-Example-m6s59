# C Off-by-One Error
This repository demonstrates a common off-by-one error in C programming.  The `bug.c` file contains the erroneous code.  The `bugSolution.c` file provides a corrected version.

**Understanding the Error:**
In C, array indices start at 0. Therefore, an array of size 5 has valid indices from 0 to 4. The error occurs when a pointer is incremented beyond the valid range. Accessing memory outside of the array leads to undefined behavior.

**How to fix:**
Ensure array access remains within the bounds of the allocated memory. The solution file demonstrates correct pointer usage and boundary checking.