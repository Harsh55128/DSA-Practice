# Sort 0s, 1s and 2s

**Difficulty:** Medium  
**Points:** 4  
**Expected Time:** 10 minutes

## Problem Statement

Given an array `arr[]` containing only `0`s, `1`s, and `2`s, sort the array in ascending order.

## Examples

### Example 1

**Input:**
```text
arr[] = [0, 1, 2, 0, 1, 2]
```

**Output:**
```text
[0, 0, 1, 1, 2, 2]
```

**Explanation:** The `0`s, `1`s, and `2`s are grouped in ascending order.

### Example 2

**Input:**
```text
arr[] = [0, 1, 1, 0, 1, 2, 1, 2, 0, 0, 0, 1]
```

**Output:**
```text
[0, 0, 0, 0, 0, 1, 1, 1, 1, 1, 2, 2]
```

**Explanation:** The `0`s, `1`s, and `2`s are grouped in ascending order.

## Follow-up

Can you solve this problem in **one pass** using only **constant extra space**?

## Constraints

- `1 <= arr.size() <= 10^5`
- `0 <= arr[i] <= 2`

## Expected Complexity

- **Time Complexity:** `O(n)`
- **Auxiliary Space:** `O(1)`

## Practice Tasks

1. Solve the problem using a counting approach.
2. Solve it using a one-pass algorithm.
3. Explain how your algorithm achieves `O(n)` time complexity and `O(1)` auxiliary space.

**Challenge:** Try to solve the problem without using any built-in sorting function.
