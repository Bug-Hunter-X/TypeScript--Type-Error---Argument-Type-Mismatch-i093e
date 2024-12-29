# TypeScript Type Error: Argument Type Mismatch

This repository demonstrates a common TypeScript error: passing an array to a function expecting a single string argument.

The `bug.ts` file contains the erroneous code.  The `bugSolution.ts` file provides a corrected version.

The error arises because the `greeter` function is explicitly typed to accept a single string.  Attempting to pass an array results in a type error during compilation.

The solution demonstrates two approaches:

1. Iterating through the array and calling the `greeter` function for each element.
2. Modifying the `greeter` function to accept an array of strings.