# Merge Sort

## Goal
Learn more about sorting and searching, with a focus on implementing **merge sort**.

## Assignment
Write a Java program that implements merge sort and displays the array after successive passes, as illustrated below.

## Files
- `MergeSort.java`
- `MergeSortRunner.java`

## Sample inputs

```text
9 5 3 2
19 52 3 2 7 21
68 66 11 2 42 31
```

## Sample output

```text
pass 0 [5, 9, 3, 2]
pass 1 [5, 9, 2, 3]
pass 2 [2, 3, 5, 9]

pass 0 [19, 3, 52, 2, 7, 21]
pass 1 [3, 19, 52, 2, 7, 21]
pass 2 [3, 19, 52, 2, 7, 21]
pass 3 [3, 19, 52, 2, 7, 21]
pass 4 [2, 3, 7, 19, 21, 52]

pass 0 [68, 11, 66, 2, 42, 31]
pass 1 [11, 66, 68, 2, 42, 31]
pass 2 [11, 66, 68, 2, 31, 42]
pass 3 [11, 66, 68, 2, 31, 42]
pass 4 [2, 11, 31, 42, 66, 68]
```

## Algorithm guidance from the handout

The supplied algorithm describes recursive `mergesort(array, front, back)` and a helper `merge(array, front, back)`:

1. Find the midpoint of the current range.
2. Stop recursing when the range cannot be divided further.
3. Recursively sort the left and right halves.
4. Merge the sorted halves using a temporary array.
5. Copy merged values back into the original array.

The handout's pseudocode uses a temporary array of size `back - front`, which indicates **half-open ranges**: `front` inclusive and `back` exclusive. Be consistent about this convention in both recursive and merge methods.

## Before submitting
Check that each array ends in ascending order, that both halves are merged correctly, and that the displayed passes follow the assigned format. Commit your work to the designated lab branch.

*Adapted from the supplied A+ Computer Science assignment, “Merge Sort.”*
