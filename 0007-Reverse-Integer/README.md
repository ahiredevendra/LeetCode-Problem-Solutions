# 7. Reverse Integer

LeetCode Problem: 7. Reverse Integer https://leetcode.com/problems/reverse-integer/

Difficulty: Medium

Language: Java

Problem Description: Given a signed 32-bit integer x, return x with its digits reversed. If reversing the integer causes it to go outside the signed 32-bit integer range, return 0.

Approach: Mathematical Reversal

1. Initialize rev = 0 to store the reversed number.
2. Extract the last digit using x % 10.
3. Remove the last digit from x using x / 10.
4. Check for integer overflow before updating rev.
5. If the reversed number exceeds the integer range, return 0.
6. Otherwise, update rev = rev * 10 + rem.
7. Repeat until x becomes 0.
8. Return the reversed number.

Status: Solved ✅
