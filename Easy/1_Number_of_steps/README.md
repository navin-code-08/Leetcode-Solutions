1342. Number of Steps to Reduce a Number to Zero
Problem Description

Given an integer num, return the number of steps required to reduce it to 0.

Rules:
    i) If the current number is even, divide it by 2.
    ii) If the current number is odd, subtract 1 from it.
    iii) Continue the process until the number becomes 0.

Example
Example 1

Input
num = 14
Steps
14 → 7 → 6 → 3 → 2 → 1 → 0
Output
6

Example 2

Input

num = 8

Steps

8 → 4 → 2 → 1 → 0

Output

4
Example 3

Input

num = 123

Output

12
⏱ Time Complexity

O(log n)

Explanation:

Each division by 2 reduces the number significantly.

The number of divisions possible is approximately log₂(n).

Subtraction operations occur only when the number is odd.

💾 Space Complexity

O(1)

No extra space is used other than a few variables.
