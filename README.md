# Ada Constraint_Error Example

This repository demonstrates a common Ada error: `Constraint_Error` due to accessing an array element with an out-of-bounds index.

The `bug.ada` file contains code that attempts to access an element beyond the defined bounds of an array.  The `bugSolution.ada` file shows how to prevent this error by adding checks to ensure the index remains within the valid range.

This example highlights the importance of robust index checking in Ada to prevent runtime errors and maintain program stability.