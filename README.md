# R Integer Overflow Bug

This repository demonstrates an integer overflow bug in R and provides a solution.  The bug occurs when attempting to calculate 2^1000, which exceeds the maximum value that R can represent as an integer.  The solution involves using a library that handles arbitrary-precision arithmetic to correctly calculate the result.

## Bug
The `bug.r` file contains code that attempts to calculate 2^1000 directly, which leads to an integer overflow resulting in incorrect output. 

## Solution
The `bugSolution.r` file demonstrates a solution using the `Rmpfr` package for arbitrary-precision arithmetic.  This library allows for calculations involving extremely large numbers without the risk of overflow.
