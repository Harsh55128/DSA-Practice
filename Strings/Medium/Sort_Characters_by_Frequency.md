# Sort Characters by Frequency

## Problem Statement

Given a string `s`, sort its characters in **descending order based on their frequency**.

The frequency of a character is the number of times it appears in the string.

If two characters have the same frequency, their relative order does not matter.

## Constraints

* `1 <= s.length <= 10^5`
* `s` consists of uppercase and lowercase English letters (`A-Z`, `a-z`).
* The output should contain all characters from the original string.
* Characters with higher frequency must appear before characters with lower frequency.

## Examples

### Example 1

**Input:**

```text
"tree"
```

**Output:**

```text
"eert"
```

**Explanation:**

* `e` appears 2 times.
* `t` appears 1 time.
* `r` appears 1 time.

Therefore, `e` appears before `t` and `r`.

---

### Example 2

**Input:**

```text
"cccaaa"
```

**Output:**

```text
"cccaaa"
```

**Explanation:**

Both `c` and `a` appear 3 times, so either order is valid.

---

### Example 3

**Input:**

```text
"abbccc"
```

**Output:**

```text
"cccabb"
```

**Explanation:**

* `c` appears 3 times.
* `b` appears 2 times.
* `a` appears 1 time.

Therefore, the characters are arranged in descending order of frequency.

---

### Example 4

**Input:**

```text
"banana"
```

**Output:**

```text
"aaannb"
```

**Explanation:**

* `a` appears 3 times.
* `n` appears 2 times.
* `b` appears 1 time.

Therefore, the sorted string is `"aaannb"`.
