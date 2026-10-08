# Kadane's Algorithm

## Problem Statement

You are given an integer array `arr[]`. Find the **maximum sum of a subarray** containing at least one element.

A subarray is a contiguous part of an array.

## Examples

### Example 1

**Input:**

```text
arr[] = [2, 3, -8, 7, -1, 2, 3]
```

**Output:**

```text
11
```

**Explanation:**

The subarray `[7, -1, 2, 3]` has the maximum sum:

```text
7 + (-1) + 2 + 3 = 11
```

---

### Example 2

**Input:**

```text
arr[] = [-2, -4]
```

**Output:**

```text
-2
```

**Explanation:**

The subarray `[-2]` has the maximum sum.

---

### Example 3

**Input:**

```text
arr[] = [5, 4, 1, 7, 8]
```

**Output:**

```text
25
```

**Explanation:**

The entire array has the maximum sum:

```text
5 + 4 + 1 + 7 + 8 = 25
```

## Constraints

* `1 <= arr.length <= 10^5`
* `-10^4 <= arr[i] <= 10^4`
* The subarray must contain at least one element.
