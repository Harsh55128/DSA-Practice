# Longest Common Prefix

## Problem Statement

Given an array of strings, find the **longest common prefix** shared by all the strings.

If there is no common prefix, return an empty string `""`.

## Constraints

* `1 <= strs.length <= 200`
* `1 <= strs[i].length <= 200`
* `strs[i]` consists of only lowercase English letters (`a-z`).

## Examples

### Example 1

**Input:**

```text
["flower", "flow", "flight"]
```

**Output:**

```text
"fl"
```

### Example 2

**Input:**

```text
["dog", "racecar", "car"]
```

**Output:**

```text
""
```

### Example 3

**Input:**

```text
["interspecies", "interstellar", "interstate"]
```

**Output:**

```text
"inters"
```

### Example 4

**Input:**

```text
["apple", "app", "application"]
```

**Output:**

```text
"app"
```
