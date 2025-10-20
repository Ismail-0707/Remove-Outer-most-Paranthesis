# 🧮 LeetCode 1021 — Remove Outermost Parentheses

## 🧩 Problem Statement

You are given a **valid parentheses string** `s`.  
A **primitive parentheses string** is a non-empty valid string that cannot be split into two non-empty valid parentheses strings.

Your task is to **remove the outermost parentheses** from every primitive part of the string and return the resulting string.

---

### 🔹 Example 1
```cpp
Input: s = "(()())(())"
Output: "()()()"

Explanation:
Primitive parts: "(()())" and "(())"
Removing the outermost parentheses:
"(()())" → "()()"
"(())" → "()"
Result → "()()()"
```
### 🔹 Example 2
```
Input: s = "(()())(())(()(()))"
Output: "()()()()(())"
```
