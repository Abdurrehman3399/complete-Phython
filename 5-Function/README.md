# Functions & Recursion in Python

This project explains the basic concepts of **functions** and **recursion** in Python.

---

##  What is a Function?

A **function** is a reusable block of code that performs a specific task.
It helps to:

- Reduce repetition
- Improve readability
- Organize code

---

##  Example of Function

```python
def sum(a, b, c):
    d = a + b + c
    average = d / 3
    return average

print(sum(45, 85, 45))
```

---

##  Recursion in Python

###  What is Recursion?

Recursion is a programming technique where a function calls itself to solve a problem.
Instead of using loops, recursion breaks a problem into smaller sub-problems.

###  Key Concepts

- **Base Case** → Stops the recursion
- **Recursive Case** → Function calls itself

---

###  Example of Recursion

```python
def factorial(n):
    if n == 0 or n == 1:   # Base case
        return 1
    return n * factorial(n - 1)   # Recursive call

print(factorial(5))
```

###  Output

```text
120
```

---

##  Conclusion

- Functions make code reusable and clean
- Recursion solves problems step-by-step
- Always include a base case to avoid infinite loops

---

##  Author

**Abdur-Rehman Javed**
