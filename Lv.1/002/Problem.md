
## Problem Statement

Given a string `s`, find the index of the nearest occurrence of the same character that appeared before at each position in `s`.

For example, if `s="banana"`, the process proceeds as follows by reading each character from left to right:

- 'b' has no same character appearing before, so it's represented as -1.
- 'a' has no same character appearing before, so it's represented as -1.
- 'n' has no same character appearing before, so it's represented as -1.
- 'a' has another 'a' two positions before, so it's represented as 2.
- 'n' has another 'n' two positions before, so it's represented as 2.
- 'a' has 'a' two and four positions before, but the nearest occurrence is two positions before, so it's represented as 2.

Therefore, the final result would be `[-1, -1, -1, 2, 2, 2]`.

## Function Specification

Complete the function `solution` that performs the defined operation when given the string `s`.
