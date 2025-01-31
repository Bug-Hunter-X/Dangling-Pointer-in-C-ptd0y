# Dangling Pointer in C
This repository demonstrates a common error in C programming: creating and using a dangling pointer.
A dangling pointer points to a memory location that has been freed or is no longer valid. Dereferencing a dangling pointer leads to undefined behavior, which can cause crashes, unexpected results, or security vulnerabilities.

The `bug.c` file contains code that creates a dangling pointer. The `bugSolution.c` file shows how to avoid this problem.