# All Subsequences of a String

## Problem Statement

Given a string `s`, generate all possible **subsequences** of the string, including the empty subsequence, and return them in **lexicographical order**.

A subsequence is obtained by deleting zero or more characters from the string without changing the relative order of the remaining characters.

## Examples

### Example 1

**Input:**

```text
s = "abc"
```

**Output:**

```text
["", "a", "ab", "abc", "ac", "b", "bc", "c"]
```

**Explanation:**

All possible subsequences of `"abc"` are:

```text
""
"a"
"b"
"c"
"ab"
"ac"
"bc"
"abc"
```

After arranging them in lexicographical order:

```text
["", "a", "ab", "abc", "ac", "b", "bc", "c"]
```

---

### Example 2

**Input:**

```text
s = "aa"
```

**Output:**

```text
["", "a", "a", "aa"]
```

**Explanation:**

The two `"a"` subsequences come from different positions in the original string, so they are both included.

---

## Constraints

* `1 <= s.length <= 16`
* `s` consists of lowercase English letters (`a-z`).
* Duplicate subsequences should be included if they are generated from different positions in the string.
* The empty subsequence must be included.
* The output should be in lexicographical order.
