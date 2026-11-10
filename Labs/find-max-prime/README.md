# Find Max Prime

## Goal
Practice class and method creation, two-dimensional arrays (matrices), nested loops, and searching.

## Assignment
Create a class that randomly fills an integer matrix with values from **1 through an upper bound, inclusive**. Implement a method to find the **max prime**: the prime number in the matrix with the **largest surrounding sum**.

## Files
- `MatrixSearch2.java`
- `MatrixSearch2Runner.java`

## Sample inputs
Each input is presented as three values: matrix rows, matrix columns, and the upper bound.

```text
20, 15, 50
15, 15, 75
7, 7, 100
```

The original assignment provides example randomly generated matrices. Because the values are random, your matrix and result may differ from those examples.

For the matrices shown in the original handout, the reported results are:

```text
Max Prime = 47
Max Prime = 41
Max Prime = 67
```

## Expected behavior
- Generate a matrix of the requested dimensions.
- Populate each cell with a random integer in the inclusive range `1` to the specified upper bound.
- Search for prime-valued cells.
- Determine which prime has the largest surrounding sum.
- Display the matrix and the resulting max prime, following the general sample format.

## Clarification needed
The original handout does **not** define precisely which neighboring cells contribute to a prime's “surrounding sum,” or how edges and corners are handled. Follow the convention established in class or in the provided starter code.

## Before submitting
Verify matrix dimensions, generated-number bounds, prime identification, and safe handling of matrix boundaries. Commit your work to the designated lab branch.

*Adapted from the supplied A+ Computer Science assignment, “Find Max Prime.”*
