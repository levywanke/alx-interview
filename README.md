# 0x00. Pascal's Triangle

## Overview
This project involves generating Pascal's Triangle using Python. Pascal's Triangle is a triangular array where each number is the sum of the two numbers directly above it.

## Learning Objectives
- Create and manipulate lists in Python.
- Implement algorithms with nested loops and list comprehensions.
- Use basic arithmetic operations and indexing in Python.
- Write efficient and optimized code.

## Requirements
- Code will be executed on Ubuntu 18.04 LTS using Python 3.7.x.
- Use the `.py` extension for your code.
- Ensure code is PEP 8 compliant.

## Function Details
Create a function `def pascal_triangle(n):` that returns a list of lists representing Pascal’s Triangle of `n`:
- Return an empty list if `n <= 0`.
- `n` will always be an integer.

### Example
```python
#!/usr/bin/python3
"""
0-main
"""
pascal_triangle = __import__('0-pascal_triangle').pascal_triangle

def print_triangle(triangle):
    """
    Print the triangle
    """
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))
```

```sh
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
```

## Repository Details
- **GitHub repository:** `alx-interview`
- **Directory:** `0x00-pascal_triangle`
- **File:** `0-pascal_triangle.py`

