### Question 1 
```
Problem Statement

You are given a string s consisting of lowercase English letters (a–z) and digits (0–9).

Your task is to:

Identify the largest numerical value formed by consecutive digits in the string.

Return the starting index (0-based) of the first occurrence of that largest number in the string.

If the string contains no digits, return -1.



Example 1

Input:
s = "ab12cd345ef67"

Output:
6

Explanation:
The numbers in the string are 12, 345, and 67.
The largest number is 345 which starts at index 6.



Example 2

Input:
s = "a9b8c7"

Output:
1

Explanation:
The numbers are 9, 8, and 7.
The largest number is 9 starting at index 1.

Example 3

Input:
s = "abcdef"

Output:
-1

Explanation:
There are no digits in the string.

Constraints

1 <= s.length <= 10⁵

s contains only lowercase English letters and digits
```
