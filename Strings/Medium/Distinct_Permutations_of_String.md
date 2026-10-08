# Distinct Permutations of String

## Problem Statement

Given a string `s`, which may contain duplicate characters, generate all possible **unique permutations** of the string.

You may return the permutations in any order.

## Examples

### Example 1

**Input:**

```text id="8xj7k4"
s = "ABC"
```

**Output:**

```text id="3q9x1m"
["ABC", "ACB", "BAC", "BCA", "CAB", "CBA"]
```

**Explanation:**

The string `"ABC"` contains 3 distinct characters, so a total of **6 unique permutations** can be formed.

---

### Example 2

**Input:**

```text id="y5t1sp"
s = "ABSG"
```

**Output:**

```text id="d9k2cw"
["ABGS", "ABSG", "AGBS", "AGSB", "ASBG", "ASGB",
 "BAGS", "BASG", "BGAS", "BGSA", "BSAG", "BSGA",
 "GABS", "GASB", "GBAS", "GBSA", "GSAB", "GSBA",
 "SABG", "SAGB", "SBAG", "SBGA", "SGAB", "SGBA"]
```

**Explanation:**

All 4 characters are distinct, so `4! = 24` unique permutations can be formed.

---

### Example 3

**Input:**

```text id="3j6kqz"
s = "AAA"
```

**Output:**

```text id="a7w2pn"
["AAA"]
```

**Explanation:**

All characters are the same, so only one unique permutation can be formed.

---

## Constraints

* `0 <= s.length <= 9`
* `s` consists only of uppercase English alphabets (`A-Z`).
* Duplicate characters may be present in the string.
* Each unique permutation should appear only once in the output.
