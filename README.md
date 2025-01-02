# Ada Off-by-One Error Example

This repository demonstrates a common off-by-one error in Ada when iterating through arrays.  Ada arrays are 1-based, meaning the first element is accessed with index 1, not 0.

The `bug.ada` file contains code with the error.  The `bugSolution.ada` file provides the corrected code.

This example highlights the importance of carefully considering array bounds when working with Ada.
