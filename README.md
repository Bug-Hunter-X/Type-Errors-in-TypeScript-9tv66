# Type Errors in TypeScript

This repository demonstrates a common type error in TypeScript and how to resolve it.

## Bug

The `bug.ts` file contains two functions, `add` and `subtract`, which are defined to accept two numbers and return a number.  However, in the usage, string values are passed to the function, resulting in a type error. 

## Solution

The solution, found in `bugSolution.ts`, addresses the type errors by ensuring that only numbers are passed as arguments to the `add` and `subtract` functions.