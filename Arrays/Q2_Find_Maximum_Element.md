2. Find Maximum Element

## Problem Statement

Given an integer array, find the **maximum (largest) element** present in the array.

---

## Example

### Input

```text
[10, 5, 25, 8, 15]

Output
25

Explanation
The largest element in the array is 25, so the output is:
25

Concept
Maintain a max variable.
- Start with the first element as the maximum.
- Traverse the array using a loop.
- If the current element is greater than max, update max.
- At the end, max will contain the largest element.
Additional Examples
Example 2
Input:
[3, 7, 1, 9, 4]

Output:
9

Example 3
Input:
[-5, -2, -10, -1]

Output:
-1
