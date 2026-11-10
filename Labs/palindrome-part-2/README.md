# Palindrome Part II

## Goal
Practice class creation, `ArrayList`, sorting/searching, and manipulating objects stored by reference in an `ArrayList`.

## Assignment
Implement `LongPalindrome` to find palindromic substrings in a word. A palindrome must contain **at least two characters**.

Complete these methods with the specified signatures:

```java
public static ArrayList<Palin> getAllPalins(String word)
private static int insertLocation(ArrayList<Palin> list, Palin pal)
public static Palin getLongestPalin(String word)
```

- `getAllPalins` returns all palindromes contained in `word`, in **alphabetical order**, and **must call** `insertLocation`.
- `insertLocation` determines where to insert a new `Palin` so the list remains alphabetically sorted.
- `getLongestPalin` returns the longest palindrome in `word` and **must call** `getAllPalins`.

## Files
- `Palin.java`
- `LongPalindrome.java`
- `LongPalindromeRunner.java`

## Sample data and expected output

| Input | Alphabetically sorted palindromes | Longest |
|---|---|---|
| `bobcat` | `[bob]` | `bob` |
| `bobracecarcat` | `[aceca, bob, cec, racecar]` | `racecar` |
| `alligatorslikegroovycatslikemadamandrooroo` | `[ada, ama, ll, madam, oo, oo, oo, ooroo, oro, roor]` | `madam` |
| `idrovetothelibraryinmyracecartolearnaboutpanama` | `[aceca, ama, ana, cec, racecar, rar, tot]` | `racecar` |

Repeated entries in the sample output are intentional.

## Before submitting
Verify that the three required methods work together, the list remains alphabetically sorted, and the longest palindrome is correctly identified. Commit your work to the designated lab branch.

*Adapted from the supplied A+ Computer Science assignment, “Palindrome Part II.”*
