# Converge
Holds the converge code - py + js

## Problem
Input: Given 2 nouns
Output: Generate a noun as closely related to the nouns in the input

### Strategy 1

- Parse pages from wikipedia:
- Start with a page obtained from the url `https://en.wikipedia.org/wiki/Special:Random`
- Parse each line as a single element OR breakdown line into nouns and store each group of nouns as an array which is 1 element of the master array
- Each noun in one sentence gains a rank (vary rank based on sentence, paragraph, page)
- Generate a spread map for each word
- Return the word at which the two words intersect

### Strategy 2

    