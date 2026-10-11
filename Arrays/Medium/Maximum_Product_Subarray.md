# Maximum Product Subarray

**Difficulty:** Medium  
**Points:** 4

## Problem Statement

Given an array `arr[]` that contains positive and negative integers (may contain `0` as well), find the maximum product that we can get in a subarray of `arr[]`.

**Note:** It is guaranteed that the answer fits in a 32-bit integer.

## Examples

### Example 1

**Input:**
```text
arr[] = [-2, 6, -3, -10, 0, 2]
```

**Output:**
```text
180
```

**Explanation:** The subarray with the maximum product is `[6, -3, -10]` with product `6 * (-3) * (-10) = 180`.

### Example 2

**Input:**
```text
arr[] = [-1, -3, -10, 0, 6]
```

**Output:**
```text
30
```

**Explanation:** The subarray with the maximum product is `[-3, -10]` with product `(-3) * (-10) = 30`.

### Example 3

**Input:**
```text
arr[] = [2, 3, 4]
```

**Output:**
```text
24
```

**Explanation:** For an array with all positive elements, the result is the product of all elements.

## Constraints

- `1 <= arr.size() <= 10^6`
- `-100 <= arr[i] <= 100`

## Expected Complexity

- **Time Complexity:** Try to achieve `O(n)`.
- **Auxiliary Space:** Try to achieve `O(1)`.

## Practice Challenge

Solve the problem without using a brute-force approach. Think carefully about how positive numbers, negative numbers, and zeros affect the product of a subarray.
