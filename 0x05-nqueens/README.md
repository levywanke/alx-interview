# N Queens Problem

## Overview

The N Queens problem is a classic problem in computer science and mathematics where the goal is to place N non-attacking queens on an N×N chessboard. This project involves implementing a solution to the N Queens problem using a backtracking algorithm in Python.

## Project Details


The task is to write a Python program that solves the N Queens problem and prints all possible solutions. Each solution must be printed in a specific format, and the program must handle various edge cases.

## Concepts Covered

- **Backtracking Algorithms:** Understanding how to explore all potential solutions and backtrack when necessary.
- **Recursion:** Implementing recursive functions to facilitate backtracking.
- **List Manipulations:** Creating and manipulating lists to store and manage queen positions on the board.
- **Command Line Arguments:** Handling and validating command-line arguments using the `sys` module.

## Requirements

- **Python Version:** 3.4.3
- **Editors Allowed:** vi, vim, emacs
- **Code Style:** PEP 8 (version 1.7.*)
- **File Execution:** All files must be executable and start with `#!/usr/bin/python3`
- **Documentation:** Include a `README.md` file at the root of the project folder

## Tasks

### 0. N Queens

Create a Python program to solve the N Queens problem.

**Usage:** 

```bash
./0-nqueens.py N
```

**Requirements:**

- If the user provides the wrong number of arguments, print `Usage: nqueens N` and exit with status 1.
- If `N` is not an integer, print `N must be a number` and exit with status 1.
- If `N` is smaller than 4, print `N must be at least 4` and exit with status 1.
- The program should print every possible solution, one solution per line.
- The format of the solutions should be as shown in the examples below.
- Only import the `sys` module.

**Examples:**

```bash
$ ./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]

$ ./0-nqueens.py 6
[[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
[[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
[[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
[[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
```

## Resources

- **Backtracking Algorithms:** [Backtracking Introduction](#)
- **Recursion in Python:** [Recursion in Python](#)
- **List Manipulations in Python:** [Python Lists](#)
- **Command Line Arguments in Python:** [Command Line Arguments in Python](#)
- **Mock Interview:** [Mock Interview](#)