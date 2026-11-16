# 35. Search Insert Position

LeetCode Problem: 35. Search Insert Position https://leetcode.com/problems/search-insert-position/description/

Difficulty: Easy

Language: Java

Problem Description: Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be inserted in order.

Approach: Binary Search

1. Initialize two pointers i = 0 and j = nums.length - 1.
2. Calculate the middle index using mid = i + (j - i) / 2.
3. If nums[mid] equals the target, return mid.
4. If the target is smaller than nums[mid], search in the left half by updating j = mid - 1.
5. Otherwise, search in the right half by updating i = mid + 1.
6. If the target is not found, return i as the insertion position.

Status: Solved ✅
