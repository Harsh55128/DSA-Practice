Union of Two Sorted Arrays

Topic: Arrays, Two Pointers

Problem Statement

Given two sorted arrays nums1 and nums2, return an array that contains the union of these two arrays. The elements in the union must be in ascending order.

The union of two arrays contains all distinct values present in either array or both arrays. Each element must appear only once in the result.

Examples

Example 1

Input:

nums1 = [1, 2, 3, 4, 5]
nums2 = [1, 2, 7]

Output:

[1, 2, 3, 4, 5, 7]

Explanation:

The elements 1 and 2 are common to both arrays. The elements 3, 4, and 5 are from nums1, and 7 is from nums2.

Example 2

Input:

nums1 = [3, 4, 6, 7, 9, 9]
nums2 = [1, 5, 7, 8, 8]

Output:

[1, 3, 4, 5, 6, 7, 8, 9]

Explanation:

The element 7 is common to both arrays. The elements 3, 4, 6, and 9 are from nums1, while 1, 5, and 8 are from nums2. Duplicate elements appear only once in the union.
