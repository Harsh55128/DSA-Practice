# Minimum Jumps

## Problem Statement

You are given an array `arr[]` of non-negative integers. Each element represents the **maximum number of steps** you can jump forward from that position.

For example:

* If `arr[i] = 3`, you can jump to index `i + 1`, `i + 2`, or `i + 3`.
* If `arr[i] = 0`, you cannot jump forward from that position.

Find the **minimum number of jumps** needed to move from the first position of the array to the last position.

**Note:** Return `-1` if it is not possible to reach the last position.

## Examples

### Example 1

**Input:**

```text
arr[] = [1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9]
```

**Output:**

```text
3
```

**Explanation:**

First, jump from the 1st element to the 2nd element. From there, jump to the 5th element, and then jump to the last element.

---

### Example 2

**Input:**

```text
arr[] = [1, 4, 3, 2, 6, 7]
```

**Output:**

```text
2
```

**Explanation:**

First, jump from the 1st element to the 2nd element, and then jump to the last element.

---

### Example 3

**Input:**

```text
arr[] = [0, 10, 20]
```

**Output:**

```text
-1
```

**Explanation:**

We cannot move from the first element because its value is `0`.

## Constraints

* `2 <= arr.length <= 10^5`
* `0 <= arr[i] <= 10^5`
