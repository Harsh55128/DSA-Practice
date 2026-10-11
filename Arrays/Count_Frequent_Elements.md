# Count Frequent Elements

**Solved**

Difficulty: **Easy**  
Accuracy: **58.35%**  
Submissions: **144K+**  
Points: **2**  
Average Time: **45m**

Given an array **arr[]** of n integers and an integer **k**, find the count of elements that appear more than **n/k** times in the array.

## Examples

### Example 1

**Input:**  
arr[] = [3, 1, 2, 2, 1, 2, 3, 3], k = 4

**Output:**  
2

**Explanation:**  
The elements 2 and 3 each occur 3 times, which is more than n/k = 2.

### Example 2

**Input:**  
arr[] = [2, 3, 3, 2], k = 3

**Output:**  
2

**Explanation:**  
Both 2 and 3 appear 2 times in the array, which is more than n/k.

## Constraints

- arr.size() ≤ 10⁶
- 0 ≤ arr[i] ≤ 10⁸
- 1 ≤ k ≤ arr.size()
