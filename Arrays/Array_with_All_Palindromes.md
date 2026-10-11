# Array with All Palindromes

**Difficulty:** Basic  
**Points:** 1  
**Average Time:** 15 minutes

## Problem Statement

Given an array `arr[]` of positive integers, return `true` if all the array elements are palindromes; otherwise, return `false`.

## Examples

### Example 1

**Input:**
```text
arr[] = [111, 222, 333, 444, 555]
```

**Output:**
```text
true
```

**Explanation:**

- `arr[0] = 111`, which is a palindrome number.
- `arr[1] = 222`, which is a palindrome number.
- `arr[2] = 333`, which is a palindrome number.
- `arr[3] = 444`, which is a palindrome number.
- `arr[4] = 555`, which is a palindrome number.

As all numbers are palindromes, the function returns `true`.

### Example 2

**Input:**
```text
arr[] = [121, 131, 20]
```

**Output:**
```text
false
```

**Explanation:** `20` is not a palindrome, so the function returns `false`.

## Constraints

- `1 <= arr.size() <= 100`
- `1 <= arr[i] <= 10^9`

## Practice Challenge

1. Write a function to check whether a number is a palindrome.
2. Check every element of the array.
3. If any element is not a palindrome, return `false`.
4. If all elements are palindromes, return `true`.

**Challenge:** Solve the problem without converting the integers into strings.
