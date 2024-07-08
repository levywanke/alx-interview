# 0x02. Minimum Operations

## Overview
In this project, you will learn to calculate the minimum number of operations needed to achieve a given number of characters in a text file using only "Copy All" and "Paste" operations. This involves understanding several key algorithmic and mathematical concepts to devise an efficient solution.

## Concepts Needed
To tackle this problem, you should be familiar with the following concepts:

### Dynamic Programming
- **Description:** Breaks down the problem into simpler subproblems and builds up the solution.
- **Resource:** [Dynamic Programming (GeeksforGeeks)](https://www.geeksforgeeks.org/dynamic-programming/)

### Prime Factorization
- **Description:** Helps in reducing the problem to finding the sum of the prime factors of the target number `n`.
- **Resource:** [Prime Factorization (Khan Academy)](https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:polynomials/x2f8bb11595b61c86:factoring-polynomials/v/prime-factorization)

### Code Optimization
- **Description:** Approaching problems from an optimization perspective to find the most efficient solution.
- **Resource:** [How to Optimize Python Code](https://towardsdatascience.com/how-to-optimize-python-code-2c36c7b9e1d4)

### Greedy Algorithms
- **Description:** Solving problems by choosing the best option at each step.
- **Resource:** [Greedy Algorithms (GeeksforGeeks)](https://www.geeksforgeeks.org/greedy-algorithms/)

### Basic Python Programming
- **Description:** Proficiency in Python, including loops, conditionals, and functions, is necessary to implement the solution.
- **Resource:** [Python Functions (Python Official Documentation)](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

## Additional Resources
- [Mock Technical Interview](https://www.pramp.com/)

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3
- All files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A `README.md` file at the root of the project folder is mandatory
- Your code should be documented
- Your code should use the PEP 8 style (version 1.7.x)
- All files must be executable

## Tasks

### 0. Minimum Operations
Write a method that calculates the fewest number of operations needed to result in exactly `n` 'H' characters in the file.

**Prototype:** `def minOperations(n)`

- Returns an integer
- If `n` is impossible to achieve, return `0`

**Example:**
```python
n = 9

H => Copy All => Paste => HH => Paste => HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6
```

**Test File:**
```python
carrie@ubuntu:~/0x02-minoperations$ cat 0-main.py
#!/usr/bin/python3
"""
Main file for testing
"""

minOperations = __import__('0-minoperations').minOperations

n = 4
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))

n = 12
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))
carrie@ubuntu:~/0x02-minoperations$
carrie@ubuntu:~/0x02-minoperations$ ./0-main.py
Min number of operations to reach 4 characters: 4
Min number of operations to reach 12 characters: 7
carrie@ubuntu:~/0x02-minoperations$
```

- **File:** `0-minoperations.py`
