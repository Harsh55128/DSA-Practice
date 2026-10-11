# Longest Consecutive Subsequence

**Difficulty:** Medium  
**Points:** 4  
**Average Time:** 25 minutes

## Problem Statement

Given an array `arr[]` of non-negative integers, find the length of the longest subsequence such that the elements in the subsequence are consecutive integers. The consecutive numbers can be in any order.

## Examples

### Example 1

**Input:**
```text
arr[] = [2, 6, 1, 9, 4, 5, 3]
```

**Output:**
```text
6
```

**Explanation:** The consecutive numbers are `1, 2, 3, 4, 5, 6`. These 6 numbers form the longest consecutive subsequence.

### Example 2

**Input:**
```text
arr[] = [1, 9, 3, 10, 4, 20, 2]
```

**Output:**
```text
4
```

**Explanation:** `1, 2, 3, 4` is the longest consecutive subsequence.

### Example 3

**Input:**
```text
arr[] = [15, 13, 12, 14, 11, 10, 9]
```

**Output:**
```text
7
```

**Explanation:** The longest consecutive subsequence is `9, 10, 11, 12, 13, 14, 15`, which has a length of 7.

## Constraints

- `1 <= arr.size() <= 10^5`
- `0 <= arr[i] <= 10^5`

## Expected Complexity

Try to achieve:

- **Time Complexity:** `O(n)`
- **Auxiliary Space:** `O(n)`

## Practice Challenge

1. First, try solving the problem by sorting the array.
2. Think about how a `HashSet` can help you find consecutive elements efficiently.
3. Handle duplicate elements correctly.
4. Try to achieve `O(n)` time complexity without sorting the array.

**Challenge:** Can you find the longest consecutive subsequence in linear time?
