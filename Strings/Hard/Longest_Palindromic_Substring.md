# Longest Palindromic Substring

## Problem Statement

Given a string `s`, find the **longest palindromic substring** in `s`.

A palindrome is a string that reads the same forward and backward.

If there are multiple palindromic substrings with the same maximum length, return any one of them.

## Constraints

* `1 <= s.length <= 1000`
* `s` consists of uppercase and lowercase English letters (`A-Z`, `a-z`).

## Examples

### Example 1

**Input:**

```text
"babad"
```

**Output:**

```text
"bab"
```

**Explanation:**

`"bab"` is a palindrome and is one of the longest palindromic substrings.

`"aba"` is also a valid answer.

---

### Example 2

**Input:**

```text
"cbbd"
```

**Output:**

```text
"bb"
```

**Explanation:**

`"bb"` is the longest palindromic substring.

---

### Example 3

**Input:**

```text
"racecar"
```

**Output:**

```text
"racecar"
```

**Explanation:**

The entire string is a palindrome.

---

### Example 4

**Input:**

```text
"abcd"
```

**Output:**

```text
"a"
```

**Explanation:**

There is no palindromic substring of length greater than `1`. Any single character is a valid palindrome.
