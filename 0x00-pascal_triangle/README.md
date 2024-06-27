# Pascal's Triangle

## Overview
This project involves implementing Pascal's Triangle in Python. Pascal's Triangle is a triangular array of the binomial coefficients. In this task, you will create a function that generates Pascal's Triangle up to a specified number of rows.

## Learning Objectives
By the end of this project, you should be able to:

1. Understand the structure and properties of Pascal's Triangle.
2. Use Python lists and list comprehensions.
3. Implement functions with appropriate parameters and return values.
4. Utilize loops and conditional statements effectively.
5. Handle arithmetic operations and indexing in Python.
6. Optimize code for efficiency.

## Requirements
- Python version: 3.x
- The function must be implemented in a single file named `0-pascal_triangle.py`.

## Project Tasks

### Task 0: Pascal's Triangle
- **Objective:** Create a function `def pascal_triangle(n):` that returns a list of lists representing Pascal’s Triangle up to `n` rows.
- **Specifications:**
  - Returns an empty list if `n <= 0`.
  - Assume `n` is always an integer.

#### Example
```python
guillaume@ubuntu:~/0x00$ cat 0-main.py
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

guillaume@ubuntu:~/0x00$ 
guillaume@ubuntu:~/0x00$ ./0-main.py
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
guillaume@ubuntu:~/0x00$ 
```

### Repository Structure
- **Repository:** `alx-interview`
- **Directory:** `0x00-pascal_triangle`
- **File:** `0-pascal_triangle.py`

## Additional Resources
- [Pascal's Triangle - Numberphile](https://www.youtube.com/watch?v=XMriWTvPXHI)
- [What is Pascal’s Triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle)
- [Python Lists and List Comprehensions](https://docs.python.org/3/tutorial/datastructures.html)

## Mock Technical Interview
- Practice interview questions to strengthen your understanding of the concepts.