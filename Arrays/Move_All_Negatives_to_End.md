# Move All Negatives to End

## Problem Statement

Given an unsorted array `arr[]` containing both **negative and positive integers**, move all negative elements to the **end of the array**.

The **relative order of positive elements and negative elements must remain unchanged**.

**Note:** Modify the array **in-place**. Do not return a separate array.

## Examples

### Example 1

**Input:**

```text
arr[] = [1, -1, 3, 2, -7, -5, 11, 6]
```

**Output:**

```text
[1, 3, 2, 11, 6, -1, -7, -5]
```

**Explanation:**

All positive elements are moved to the beginning and all negative elements to the end, while maintaining their original relative order.

---

### Example 2

**Input:**

```text
arr[] = [-5, 7, -3, -4, 9, 10, -1, 11]
```

**Output:**

```text
[7, 9, 10, 11, -5, -3, -4, -1]
```

**Explanation:**

The relative order of positive elements (`7, 9, 10, 11`) and negative elements (`-5, -3, -4, -1`) remains unchanged.

## Constraints

* `1 <= arr.length <= 10^6`
* `-10^9 <= arr[i] <= 10^9`
* The array must be modified **in-place**.
* The relative order of positive and negative elements must not change.
