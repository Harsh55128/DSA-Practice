# Find All Anagrams of a Pattern

## Problem Statement

Given two strings `s` and `p`, find all starting indices in `s` where an **anagram of `p`** occurs.

An anagram is a string that contains the same characters with the same frequencies, but the characters may be arranged in a different order.

Return the list of starting indices in any order.

## Constraints

* `1 <= s.length <= 10^5`
* `1 <= p.length <= 10^4`
* `s` and `p` consist of lowercase English letters (`a-z`).
* The length of `p` will not be greater than the length of `s`.

## Examples

### Example 1

**Input:**

```text
s = "cbaebabacd"
p = "abc"
```

**Output:**

```text
[0, 6]
```

**Explanation:**

Anagrams of `"abc"` are:

```text
"cba" → index 0
"bac" → index 6
```

Therefore, the answer is `[0, 6]`.

---

### Example 2

**Input:**

```text
s = "abab"
p = "ab"
```

**Output:**

```text
[0, 1, 2]
```

**Explanation:**

The substrings `"ab"`, `"ba"`, and `"ab"` are all anagrams of `"ab"`.

---

### Example 3

**Input:**

```text
s = "abcdef"
p = "xy"
```

**Output:**

```text
[]
```

**Explanation:**

No substring of `s` is an anagram of `"xy"`.

---

### Example 4

**Input:**

```text
s = "baa"
p = "aa"
```

**Output:**

```text
[1]
```

**Explanation:**

The substring `"aa"` starting at index `1` is an anagram of `"aa"`.
