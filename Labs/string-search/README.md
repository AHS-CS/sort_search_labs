# String Search

## Lab Goal

This lab is designed to teach you more about sorting and searching.

## Lab Description

Write methods that take a sentence and a word or letter and determine how many times the word or letter occurs in the sentence.

You will complete the `StringSearch` class, which contains two methods:

### `countWords(String sent, String word)`

Counts the number of occurrences of `word` in `sent`.

- There may be multiple occurrences of the word.
- The word may not occur at all.
- You must use `indexOf()` to complete this method.
- Make sure you choose the correct version of `indexOf()`.

### `countLetters(String sent, String letter)`

Counts the number of occurrences of `letter` in `sent`.

- There may be multiple occurrences of the letter.
- The letter may not occur at all.
- You will need to use `substring()` and `equals()` to complete this method.

## Required Files

- `StringSearch.java`
- `StringSearchRunner.java`

## Sample Data

Use the following inputs to test your methods:

| Sentence | Word or Letter |
|---|---|
| `"computerscience"` | `"t"` |
| `"computerscience"` | `"to"` |
| `"onetwoonetwofun"` | `"n"` |
| `"onefredonetwodog"` | `"one"` |
| `"odogdogdogdogo"` | `"o"` |
| `"niininininininininini"` | `"ni"` |

## Sample Output

```text
1
0
3
2
6
10
```

Your methods should produce the corresponding results for the sample data.

## Submission

Submit your completed Java files:

- `StringSearch.java`
- `StringSearchRunner.java`

Make sure your methods return the correct counts for the sample data.