# 0x09. Island Perimeter

## Curriculum
This project is part of the Short Specializations under the ALX program, focusing on algorithms and Python programming.

### Project Details:
## Project Description
The objective of the “0. Island Perimeter” project is to calculate the perimeter of an island within a grid. The grid is represented by a 2D array of integers, where `0` represents water and `1` represents land. You need to utilize your understanding of 2D arrays, conditional logic, and algorithmic problem-solving to accurately determine the perimeter of the island.

### Key Concepts:
- **2D Arrays (Matrices):**
  - Access and iterate over elements in a 2D array.
  - Navigate through adjacent cells (horizontally and vertically).

- **Conditional Logic:**
  - Apply conditions to determine if a cell contributes to the perimeter of the island.

- **Counting Techniques:**
  - Develop a method to count the edges that contribute to the island’s perimeter.

- **Problem-Solving Strategies:**
  - Break down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.

- **Python Programming:**
  - Utilize nested loops for iterating over grid cells.
  - Implement conditional statements to check the status of adjacent cells.

### Resources:
- **Python Official Documentation:**
  - [Nested Lists](https://docs.python.org/3/tutorial/datastructures.html#nested-list-comprehensions)
  
- **GeeksforGeeks Articles:**
  - [Python Multi-dimensional Arrays](https://www.geeksforgeeks.org/python-multi-dimensional-array/)

- **TutorialsPoint:**
  - [Python Lists](https://www.tutorialspoint.com/python/python_lists.htm)

- **YouTube Tutorials:**
  - [Python 2D Arrays and Lists](https://www.youtube.com/watch?v=kTEYj1y8jko)

By understanding these concepts and utilizing the provided resources, you will be equipped to approach the problem methodically, iterating over the grid and applying logical operations to determine the island’s perimeter.

## Requirements

### General:
- **Editors Allowed:** `vi`, `vim`, `emacs`
- **Python Version:** 3.4.3
- **OS:** Ubuntu 20.04 LTS
- **Style:** PEP 8 (version 1.7)
- **Mandatory Files:** 
  - All files should end with a new line.
  - The first line of all your files should be exactly `#!/usr/bin/python3`.
  - A `README.md` file at the root of the project folder is mandatory.
- **Code Requirements:**
  - You are not allowed to import any module.
  - All modules and functions must be documented.
  - All your files must be executable.

## Tasks

### 0. Island Perimeter (Mandatory)
Create a function `def island_perimeter(grid):` that returns the perimeter of the island described in the grid.

- **Grid Specifications:**
  - The grid is a list of lists of integers.
  - `0` represents water.
  - `1` represents land.
  - Each cell is square, with a side length of 1.
  - Cells are connected horizontally/vertically (not diagonally).
  - The grid is rectangular, with width and height not exceeding 100.
  - The grid is completely surrounded by water.
  - There is only one island (or none).
  - The island doesn’t have lakes (water inside that isn’t connected to the water surrounding the island).

#### Example:
```python
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]

print(island_perimeter(grid))  # Output: 12