# 28. Find the Index of the First Occurrence in a String

LeetCode Problem: 28. Find the Index of the First Occurrence in a String https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/

Difficulty: Easy

Language: Java

Problem Description: Given two strings haystack and needle, return the index of the first occurrence of needle in haystack. If needle is not part of haystack, return -1.

Approach: Brute Force (String Matching)

1. Traverse the haystack using a loop.
2. Iterate through all possible starting positions where needle can fit.
3. Initialize j = 0 to compare characters.
4. Use a while loop to compare characters of both strings.
5. If all characters of needle match, return the starting index i.
6. If no match is found, return -1.

Status: Solved ✅
