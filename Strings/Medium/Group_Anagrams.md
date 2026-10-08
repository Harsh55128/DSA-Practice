# Group Anagrams

## Problem Statement

Given an array of strings, group the strings that are **anagrams of each other** together.

Two strings are anagrams if they contain the same characters with the same frequencies, but their order may be different.

The order of the groups and the strings within each group does not matter.

## Constraints

* `1 <= strs.length <= 10^4`
* `0 <= strs[i].length <= 100`
* `strs[i]` consists of lowercase English letters (`a-z`).
* All strings are considered case-sensitive.

## Examples

### Example 1

**Input:**

```text
["eat", "tea", "tan", "ate", "nat", "bat"]
```

**Output:**

```text
[
    ["eat", "tea", "ate"],
    ["tan", "nat"],
    ["bat"]
]
```

### Example 2

**Input:**

```text
[""]
```

**Output:**

```text
[
    [""]
]
```

### Example 3

**Input:**

```text
["a"]
```

**Output:**

```text
[
    ["a"]
]
```

### Example 4

**Input:**

```text
["listen", "silent", "enlist", "hello"]
```

**Output:**

```text
[
    ["listen", "silent", "enlist"],
    ["hello"]
]
```
