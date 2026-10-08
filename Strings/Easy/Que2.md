# String Rotation Check

Given two strings `s1` and `s2` of equal lengths, check whether `s2` is a rotated version of `s1`.

## Note

A string is considered a rotation of another string if it can be formed by moving characters from the beginning to the end or from the end to the beginning, without changing the relative order of the characters.

## Examples

### Example 1

**Input:**
```text
s1 = "abcd"
s2 = "cdab"
```

**Output:**
```text
true
```

**Explanation:**

After two right rotations, `s1` becomes `"cdab"`, which is equal to `s2`.

### Example 2

**Input:**
```text
s1 = "aab"
s2 = "aba"
```

**Output:**
```text
true
```

**Explanation:**

After one left rotation, `s1` becomes `"aba"`, which is equal to `s2`.

### Example 3

**Input:**
```text
s1 = "abcd"
s2 = "acbd"
```

**Output:**
```text
false
```

**Explanation:**

The strings are not rotations of each other because the relative order of the characters does not match any rotation.

## Constraints

- `1 <= s1.length(), s2.length() <= 10^5`
- `s1` consists only of lowercase English alphabets.
- `s2` consists only of lowercase English alphabets.

## Task

Write a Java program to determine whether `s2` is a rotation of `s1`.

Return `true` if `s2` is a rotation of `s1`; otherwise, return `false`.

## Challenge

Try solving this problem without explicitly generating every possible rotation.

**Hint:** Think about what happens when you concatenate `s1` with itself.

## Submission Guidelines

1. Write your solution in Java.
2. Test your solution using all the examples.
3. Consider edge cases, such as two identical strings.
4. Push your solution to your GitHub repository.
5. Use a meaningful commit message, such as `Solved String Rotation Check`.

## Learning Objectives

- Understand string rotation.
- Practice string manipulation in Java.
- Learn to use string concatenation to simplify a problem.
- Analyze time and space complexity.
