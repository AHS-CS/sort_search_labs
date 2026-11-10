# The Word Search

## Goal
Practice class creation, method creation, two-dimensional arrays, nested loops, and searching.

## Assignment
Load a word-search matrix and search it for specified words. Your program receives a matrix size, a String of letters used to fill the matrix, and words to search for.

## Files
- `WordSearch.java`
- `WordSearchRunner.java`

## Sample input

Matrix size: `8`

Letters (filled row by row):

```text
APPLEXYPXLHJKEEDEGGLLXXCGFPDGOGNMYNTAHUUPUQDGBTSBTHIGHMSILKXLTHISAPPLE
```

Search terms:

```text
AXE APEX CAT HEX EGG HAT COMPUTER GUM THIS TUG THIGH
```

## Expected matrix

```text
A P P L E X Y P
X L H J K E E D
E G G L L X X C
G F P D G O G N
M Y N T A H U U
P U Q D G B T S
B T H I G H M S
I L K X L T H I
```

## Expected search results

```text
APPLE was found in the matrix.
AXE was found in the matrix.
APEX was not found in the matrix.
CAT was not found in the matrix.
HEX was not found in the matrix.
EGG was found in the matrix.
HAT was found in the matrix.
COMPUTER was not found in the matrix.
GUM was not found in the matrix.
THIS was not found in the matrix.
TUG was found in the matrix.
THIGH was found in the matrix.
```

**Note:** The sample output checks `APPLE` in addition to the separately listed search terms.

## Before submitting
Confirm that the matrix is filled in the correct order and that the searches reproduce the sample results. Commit your work to the designated lab branch.

*Adapted from the supplied A+ Computer Science assignment, “The Word Search.”*
