# String Compression

## Problem Statement

Given a string, compress it by replacing consecutive repeating characters with the character followed by the number of times it appears consecutively.

If a character appears only once consecutively, include only the character.

### Example 1

**Input:**

```text
"aabcccccaaa"
```

**Output:**

```text
"a2bc5a3"
```

### Example 2

**Input:**

```text
"aaabbc"
```

**Output:**

```text
"a3b2c"
```

### Example 3

**Input:**

```text
"abcd"
```

**Output:**

```text
"abcd"
```

### Example 4

**Input:**

```text
"aaaa"
```

**Output:**

```text
"a4"
```

## Constraints

* `1 <= s.length <= 10^5`
* `s` consists of lowercase English letters (`a-z`).
* Consecutive occurrences of the same character should be treated as a single group.
* The count of a character can be greater than `9`.
