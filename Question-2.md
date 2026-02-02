### Question 2
```
You are given an array arr[] consisting of non-negative integers

You are standing at the 0th index and you need to reach the last index (n-1)

Each element arr[i] represents the maximum number of steps you can jump forward from index i

From index i, you can jump to any index in the range
i + 1 to i + arr[i] (inclusive)

If arr[i] = 0, you cannot move forward from that index

Your task is to find the minimum number of jumps required to reach the end of the array

If it is not possible to reach the last index, return -1

You are given an array arr[] consisting of non-negative integers

You are standing at the 0th index and you need to reach the last index (n-1)

Each element arr[i] represents the maximum number of steps you can jump forward from index i

From index i, you can jump to any index in the range
i + 1 to i + arr[i] (inclusive)

If arr[i] = 0, you cannot move forward from that index

Your task is to find the minimum number of jumps required to reach the end of the array

If it is not possible to reach the last index, return -1



Example 1

Input:
arr = [1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9]

Output:
3

Explanation:
Jump from index 0 → 1,
then 1 → 4,
then 4 → last index.



Example 2

Input:
arr = [1, 4, 3, 2, 6, 7]

Output:
2

Explanation:
Jump from index 0 → 1,
then 1 → last index.



Example 3

Input:
arr = [0, 10, 20]

Output:
-1

Explanation:
You cannot move forward from the first index.

```
> This was standard DP problem I solved it with memoization but some of my friends able to passed all testcases with brute-force bacuase contraints were too small
