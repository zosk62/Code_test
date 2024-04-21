## Problem Statement (The Number of p and y in String)

Suppose that a string s consisting of both lower-case and upper-case letters is given. Write a function `solution` to return True when the number of 'p' and 'y' in s are the same, and return False otherwise. Note that when there is neither 'p' nor 'y', it should always return True. Also, when comparing the number of 'p' and 'y', lower-case and upper-case are not distinguished.

For example, if s is "pPoooyY", then return true. In the case of "Pyy", return false.

### Constraints
- Length of string s: a natural number less than 50.
- String s consists of letters only.

### Examples
| s        | answer |
|----------|--------|
| "pPoooyY" | true   |
| "Pyy"     | false  |

### Example #1
Since the number of 'p' and 'y' is the same as 2, return true.

### Example #2
Since the number of 'p' is 1 whereas the number of 'y' is 2, they are different. Hence return false.

