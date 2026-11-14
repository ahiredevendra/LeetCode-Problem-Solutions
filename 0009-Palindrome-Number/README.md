# 9. Palindrome Number

LeetCode Problem: 9. Palindrome Number https://leetcode.com/problems/palindrome-number/

Difficulty: Easy

Language: Java

Problem Description: Given an integer x, return true if x is a palindrome, and false otherwise.
                     A palindrome number reads the same backward as forward.

Approach: Reverse Number

1. Check if the number is negative. If yes, return false.
2. Store the original number in a temporary variable.
3. Extract the last digit using the modulo (%) operator.
4. Build the reversed number using rev = rev * 10 + rem.
5. Remove the last digit using division (/).
6. Compare the reversed number with the original number.

Status: Solved ✅
