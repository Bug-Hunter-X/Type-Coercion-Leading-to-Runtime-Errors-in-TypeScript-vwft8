# Type Coercion Leading to Runtime Errors in TypeScript

This example demonstrates a common issue in TypeScript where type coercion can lead to unexpected runtime errors. The `add` function is designed to add two numbers, but due to TypeScript's type coercion, it compiles without error even when passed a string as an argument. This results in a runtime error.

## Bug

The `bug.ts` file contains the buggy code. It shows how TypeScript allows a string to be passed to a function expecting a number, causing the program to crash at runtime.

## Solution

The `bugSolution.ts` file demonstrates a solution to prevent this error using type guards or stricter type checking.