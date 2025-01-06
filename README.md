# R Bug: Handling Empty Vectors
This repository demonstrates a common error in R when calculating statistics on empty vectors.  The `mean()` function throws a warning when given an empty vector.  This example shows how to avoid this by adding a check for vector length before calculation.

The file `bug.r` contains the buggy code, which fails to handle the empty vector case.  `bugSolution.r` provides a corrected version.