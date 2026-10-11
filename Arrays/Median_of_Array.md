# Median of Array

**Difficulty:** Basic  
**Topic:** Arrays

## Problem Statement

Given an array `arr[]` of integers, calculate the median.

## Examples

### Example 1

**Input:**
```text
arr[] = [90, 100, 78, 89, 67]
```

**Output:**
```text
89
```

**Explanation:**

After sorting the array, the middle element is the median.

### Example 2

**Input:**
```text
arr[] = [56, 67, 30, 79]
```

**Output:**
```text
61.5
```

**Explanation:**

When the number of elements is even, the average of the two middle elements is the median.

### Example 3

**Input:**
```text
arr[] = [1, 2]
```

**Output:**
```text
1.5
```

**Explanation:**

The average of both elements is `1.5`.

## Constraints

- `1 <= arr.size()`
- `arr[i] <= 10^5`

## Task

Implement a solution to return the median of the given array.

## Expected Complexity

Try to solve the problem efficiently by sorting the array and finding its middle element(s).
