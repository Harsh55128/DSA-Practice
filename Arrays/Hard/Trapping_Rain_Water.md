# Trapping Rain Water

**Difficulty:** Hard  
**Topic:** Arrays

## Problem Statement

Given an array `arr[]` of non-negative integers representing the height of blocks, where the width of each block is `1`, calculate how much water can be trapped between the blocks after it rains.

## Examples

### Example 1

**Input:**
```text
arr = [3, 0, 1, 0, 4, 0, 2]
```

**Output:**
```text
10
```

**Explanation:**

The total trapped water is:

`0 + 3 + 2 + 3 + 0 + 2 + 0 = 10` units.

### Illustration

![Trapping Rain Water Illustration](trapping_rain_water.png)

### Example 2

**Input:**
```text
arr = [3, 0, 2, 0, 4]
```

**Output:**
```text
7
```

**Explanation:**

The total trapped water is:

`0 + 3 + 1 + 3 + 0 = 7` units.

### Example 3

**Input:**
```text
arr = [1, 2, 3, 4]
```

**Output:**
```text
0
```

**Explanation:**

No water can be trapped because there is no taller boundary on both sides of any block.

## Constraints

- Each element of `arr[]` is a non-negative integer.
- The width of every block is `1`.

## Task

Implement a solution that returns the total amount of trapped rainwater.

## Expected Complexity

Try to solve the problem in **O(n)** time. An optimized solution can use **O(1)** extra space.

## Additional Test Cases

| Input | Expected Output |
|---|---:|
| `[3, 0, 0, 2, 0, 4]` | `10` |
| `[4, 2, 0, 3, 2, 5]` | `9` |
| `[0, 1, 2, 3]` | `0` |
