# Two Sum

**Difficulty:** Easy  
**Topic:** Arrays, Hashing

## Problem Statement

Given an array of integers `nums` and an integer `target`, return the indices (0-indexed) of two elements in `nums` such that they add up to `target`.

Each input will have exactly one solution, and the same element cannot be used twice. Return the answer in any order.

## Examples

### Example 1

**Input:**
```text
nums = [1, 6, 2, 10, 3]
target = 7
```

**Output:**
```text
[0, 1]
```

**Explanation:**

`nums[0] + nums[1] = 1 + 6 = 7`

### Example 2

**Input:**
```text
nums = [1, 3, 5, -7, 6, -3]
target = 0
```

**Output:**
```text
[1, 5]
```

**Explanation:**

`nums[1] + nums[5] = 3 + (-3) = 0`

## Constraints

- Exactly one valid solution exists.
- The same element cannot be used twice.
- Return indices using 0-based indexing.
- The answer can be returned in any order.

## Task

Implement a function that returns the indices of the two numbers whose sum equals `target`.
