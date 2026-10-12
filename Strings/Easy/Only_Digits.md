# 26. Check Whether a String Contains Only Digits

## Problem Statement

Given a string `s`, check whether it contains only digits from `0` to `9`.

Return `true` if every character in the string is a digit. Otherwise, return `false`.

## Examples

### Example 1

**Input:**
```text
s = "12345"
```

**Output:**
```text
true
```

**Explanation:** Every character in the string is a digit.

### Example 2

**Input:**
```text
s = "12a45"
```

**Output:**
```text
false
```

**Explanation:** The character `'a'` is not a digit.

### Example 3

**Input:**
```text
s = "123 45"
```

**Output:**
```text
false
```

**Explanation:** The string contains a space, which is not a digit.

### Example 4

**Input:**
```text
s = "000123"
```

**Output:**
```text
true
```

**Explanation:** All characters are digits, including the leading zeros.

## Constraints

- The string may contain digits, letters, spaces, or special characters.
- An empty string should return `true` unless the problem specifies that the string must be non-empty.
  
## Complexity Analysis

- **Time Complexity:** `O(n)`, where `n` is the length of the string.
- **Space Complexity:** `O(1)`, as only a constant amount of extra space is used.

## Practice Task

Implement the solution in Java without using built-in methods such as `Character.isDigit()` or regular expressions.
