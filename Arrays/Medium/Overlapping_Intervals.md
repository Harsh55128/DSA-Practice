# Overlapping Intervals

## Problem Statement

You are given an array of intervals `arr[][]` of size `n`, where `arr[i] = [starti, endi]` represents the start and end points of the `i`th interval.

Merge all **overlapping intervals** and return the resulting array of **non-overlapping intervals**.

**Note:** Two intervals `[a, b]` and `[c, d]`, where `a <= c`, are considered overlapping if `c <= b`.

## Examples

### Example 1

**Input:**

```text
arr[][] = [[1, 3], [2, 4], [6, 8], [9, 10]]
```

**Output:**

```text
[[1, 4], [6, 8], [9, 10]]
```

**Explanation:**

The intervals `[1, 3]` and `[2, 4]` overlap. After merging, they become `[1, 4]`. The remaining intervals do not overlap.

---

### Example 2

**Input:**

```text
arr[][] = [[6, 8], [1, 9], [2, 4], [4, 7]]
```

**Output:**

```text
[[1, 9]]
```

**Explanation:**

All the intervals overlap with the interval `[1, 9]`. Therefore, after merging, the result is `[1, 9]`.

## Constraints

* `1 <= n <= 10^5`
* `0 <= starti <= endi <= 10^6`
