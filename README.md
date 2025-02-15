# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `Bug.java` file contains code that attempts to access an array element outside its valid bounds. The `BugSolution.java` file provides a corrected version.

## How to reproduce
1. Clone the repository.
2. Compile and run `Bug.java`. You will see an exception.
3. Compile and run `BugSolution.java`. This version runs without error.

## Bug Solution
The bug is fixed by ensuring that array accesses are always within the valid bounds (0 to array.length - 1). The solution utilizes a loop with an appropriate condition to prevent out-of-bounds array index access