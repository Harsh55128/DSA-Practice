# 17. Check Balanced Parentheses

## Problem Statement

Given a string containing parentheses `(` and `)`, check whether the parentheses are **balanced and correctly ordered**.

A string is balanced if:

* Every opening parenthesis `(` has a corresponding closing parenthesis `)`.
* Parentheses are closed in the correct order.
* At no point should the number of closing parentheses exceed the number of opening parentheses.

---

## Examples

### Example 1

**Input:**

```text
"(()())"
```

**Output:**

```text
true
```

**Explanation:**

Every opening parenthesis has a matching closing parenthesis, and they are correctly ordered.

---

### Example 2

**Input:**

```text
"(()"
```

**Output:**

```text
false
```

**Explanation:**

There are more opening parentheses than closing parentheses. One `(` remains unmatched.

---

### Example 3

**Input:**

```text
")("
```

**Output:**

```text
false
```

**Explanation:**

The string starts with a closing parenthesis before any opening parenthesis.

---



## Complexity

* **Time Complexity:** `O(n)`
* **Space Complexity:** `O(1)`

Where `n` is the length of the string.
