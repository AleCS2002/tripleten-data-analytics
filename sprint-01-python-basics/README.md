# Sprint 01 — Python Basics

Introduction to Python programming concepts during the TripleTen Data Analytics program.

## Overview

This sprint focused on the foundations of Python programming and logical problem solving.

Topics included:
- Variables
- Data types
- Arithmetic operations
- Strings
- Lists
- Loops
- Conditional statements
- Basic data manipulation

## Objectives

- Understand Python syntax
- Develop logical reasoning
- Work with lists and nested data structures
- Practice loops and conditional logic
- Solve practical coding exercises

## Examples of Activities

Some exercises involved:
- Filtering users based on age and purchases
- Working with nested lists
- Iterating through datasets
- Conditional analysis of user information

Example concepts practiced:

```python
for user in users:
    if 'clothes' in user[3]:
        user_name = ' '.join(user[1])
        user_age = user[2]
        print(user_name, user_age)
