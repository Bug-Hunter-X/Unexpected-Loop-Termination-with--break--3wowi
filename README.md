# Unexpected Loop Termination with 'break'
This example demonstrates a common issue with the `break` statement in JavaScript `while` loops.  The code intends to log numbers from 0 to 9, but the `break` statement exits the loop prematurely when `i` reaches 5.

## Bug
The `bug.js` file contains the buggy code. The loop terminates early, only logging numbers up to 4.

## Solution
The `bugSolution.js` file presents a corrected version. The logic is adjusted to properly achieve the intended output.