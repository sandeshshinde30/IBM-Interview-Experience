### Question 3
```
Problem Statement

You are given a string s consisting of lowercase English letters.

Your task is to recursively remove all adjacent pairs of identical characters from the string.

If two adjacent characters are the same, remove both of them.

After removal, the remaining parts of the string become adjacent and the process must be repeated recursively.

Continue this process until no adjacent identical character pairs remain.

Return the final string after all possible deletions.

Example 1

Input:
s = "abba"

Output:
""

Explanation:

"abba" → remove "bb" → "aa"

"aa" → remove "aa" → ""

String is empty, stop.



Example 2

Input:
s = "azxxzy"

Output:
"ay"

Explanation:

"azxxzy" → remove "xx" → "azzy"

"azzy" → remove "zz" → "ay"

No more adjacent duplicates.



Example 3

Input:
s = "aabccba"

Output:
""

Explanation:
All characters are removed after recursive deletions.


Constraints

1 <= s.length <= 10⁵

s contains only lowercase English letters
```

