# **DAY 005 - 19/04/2025**

**CS50P: Introduction To Programming with Python**

## LECTURE 1 - CONDITIONALS

## Table of Contents
1. [Comparison Operators](#comparison-operators)
2. [Conditional Statements](#conditional-statements)
   - [if Statement](#if-statement)
   - [elif (Else If)](#elif-else-if)
   - [else](#else)
3. [Logical Operators](#logical-operators)
   - [or](#or)
   - [and](#and)

---

## Comparison Operators

| Operator | Meaning                          | Example          |
|:---------|:----------------------------------|:-----------------|
| `>`       | Greater than                     | `5 > 3` → `True`  |
| `<`       | Less than                        | `2 < 7` → `True`  |
| `>=`      | Greater than or equal to          | `5 >= 5` → `True` |
| `<=`      | Less than or equal to             | `4 <= 6` → `True` |
| `!=`      | Not equal to                     | `5 != 3` → `True` |
| `==`      | Equal to                         | `5 == 5` → `True` |
| `%`       | Modulus (remainder after division) | `7 % 3` → `1`     |

---

## Conditional Statements

### `if` Statement
Executes a block of code if a specified condition is `True`.

```python
x = 10
if x > 5:
    print("x is greater than 5")
```
### `elif` (Else If)
Checks another condition if the previous if (or elif) was False.

## Logical Operators
### or
Returns True if at least one condition is True.

```python
x = 5
if x < 3 or x > 4:
    print("x is either less than 3 or greater than 4")
```
