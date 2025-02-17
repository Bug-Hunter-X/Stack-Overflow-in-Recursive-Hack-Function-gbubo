# Stack Overflow in Recursive Hack Function

This repository demonstrates a common error in recursive functions written in Hack: stack overflow.  The `foo` function calculates the factorial of a number recursively.  When called with a large input, it exceeds the stack's capacity, resulting in a runtime error.

The `bug.hack` file contains the buggy code, and `bugSolution.hack` provides a corrected version using iterative approach to avoid the stack overflow issue.

This example highlights the importance of carefully considering the base case and potential for unbounded recursion in recursive function implementations.