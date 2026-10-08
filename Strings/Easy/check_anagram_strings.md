# Check Anagram Strings

**Difficulty:** Medium

## Problem Statement

Given two strings `s1` and `s2`, determine whether they are anagrams of each other.

Two strings are anagrams if they contain the same characters with the same frequencies, regardless of the order of the characters.

## Examples

### Example 1

**Input:**
```text
s1 = "listen"
s2 = "silent"
```

**Output:**
```text
true
```

**Explanation:** Both strings contain the same characters with the same frequencies, but in a different order.

### Example 2

**Input:**
```text
s1 = "hello"
s2 = "world"
```

**Output:**
```text
false
```

**Explanation:** The strings do not contain the same characters with the same frequencies.

### Example 3

**Input:**
```text
s1 = "aabb"
s2 = "bbaa"
```

**Output:**
```text
true
```

**Explanation:** Both strings contain two `a` characters and two `b` characters.

### Example 4

**Input:**
```text
s1 = "aab"
s2 = "abb"
```

**Output:**
```text
false
```

**Explanation:** The character frequencies are different.

## Constraints

- `1 <= s1.length(), s2.length() <= 10^5`
- The strings contain lowercase English letters only.

## Task

Write a program that returns `true` if `s1` and `s2` are anagrams; otherwise, return `false`.
