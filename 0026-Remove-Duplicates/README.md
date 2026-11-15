# 26. Remove Duplicates from Sorted Array

LeetCode Problem: 26. Remove Duplicates from Sorted Array https://leetcode.com/problems/remove-duplicates-from-sorted-array/

Difficulty: Easy

Language: Java

Problem Description: Given an integer array nums sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. Return the number of unique elements.

Approach: Two Pointers

1. Initialize a variable k = 1 to track the position of the next unique element.
2. Traverse the array starting from index 1.
3. Compare the current element with the previous element.
4. If both elements are different, copy the current element to nums[k].
5. Increment k.
6. Return k as the number of unique elements.

Status: Solved ✅
