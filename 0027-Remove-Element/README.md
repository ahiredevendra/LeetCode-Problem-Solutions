# 27. Remove Element

LeetCode Problem: 27. Remove Element https://leetcode.com/problems/remove-element/

Difficulty: Easy

Language: Java

Problem Description: Given an integer array nums and an integer val, remove all occurrences of val in-place and return the number of remaining elements.

Approach: Two Pointers

1. Initialize a variable k = 0.
2. Traverse the array using a loop.
3. Check if the current element is not equal to val.
4. If true, copy the current element to nums[k].
5. Increment k.
6. Return k as the number of remaining elements.

Status: Solved ✅
