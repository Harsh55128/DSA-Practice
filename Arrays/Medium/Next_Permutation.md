# Next Permutation

## Problem Statement

You are given an array of integers `arr[]` representing a permutation. Rearrange the numbers into the **lexicographically smallest greater permutation** (the next permutation).

If no next permutation exists, rearrange the numbers into the **lowest possible order**, i.e., sorted in ascending order.

## Examples

### Example 1

**Input:**

```text
arr[] = [2, 4, 1, 7, 5, 0]
```

**Output:**

```text
[2, 4, 5, 0, 1, 7]
```

**Explanation:**

The next permutation of the given array is `[2, 4, 5, 0, 1, 7]`.

---

### Example 2

**Input:**

```text
arr[] = [3, 2, 1]
```

**Output:**

```text
[1, 2, 3]
```

**Explanation:**

`arr[]` is the last permutation. Therefore, the next permutation is the lowest possible permutation `[1, 2, 3]`.

---

### Example 3

**Input:**

```text
arr[] = [3, 4, 2, 5, 1]
```

**Output:**

```text
[3, 4, 5, 1, 2]
```

**Explanation:**

The next permutation of the given array is `[3, 4, 5, 1, 2]`.

## Constraints

* `1 <= arr.length <= 10^5`
