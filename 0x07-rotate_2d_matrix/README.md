# 0x07. Rotate 2D Matrix

## Curriculum
- **Short Specializations**

## Project Overview

For the “0. Rotate 2D Matrix” project, you are tasked with implementing an in-place algorithm to rotate an `n x n` 2D matrix by 90 degrees clockwise. This challenge requires a good understanding of matrix manipulation and in-place operations in Python. The project will help you develop problem-solving and algorithmic thinking skills by manipulating 2D matrices.

### Project Details

- **Start Date:** Aug 12, 2024, 6:00 AM
- **End Date:** Aug 16, 2024, 6:00 AM
- **Checker Release Date:** Aug 13, 2024, 6:00 AM
- **Auto Review:** Launched at the deadline

### Key Concepts

1. **Matrix Representation in Python**
   - Understanding how 2D matrices are represented using lists of lists.
   - Accessing and modifying elements in a 2D matrix.

2. **In-place Operations**
   - Performing operations without creating a copy of the data structure.
   - Minimizing space complexity by modifying the matrix in place.

3. **Matrix Transposition**
   - Swapping rows and columns as part of the rotation process.

4. **Reversing Rows in a Matrix**
   - Reversing the order of rows as part of the rotation.

5. **Nested Loops**
   - Using nested loops to iterate through and modify 2D matrices.

### Resources

- **Python Official Documentation**
  - [Data Structures](https://docs.python.org/3/tutorial/datastructures.html)
  - [More on Lists](https://docs.python.org/3/tutorial/introduction.html#lists)

- **GeeksforGeeks Articles**
  - [In-place Rotate Square Matrix by 90 Degrees](https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/)
  - [Transpose a Matrix in a Single Line in Python](https://www.geeksforgeeks.org/python-transpose-matrix/)

- **TutorialsPoint**
  - [Python Lists](https://www.tutorialspoint.com/python/python_lists.htm)

### Requirements

- **Editors Allowed:** vi, vim, emacs
- **Interpreter:** Ubuntu 20.04 LTS using Python 3.8.10
- **File Endings:** All files should end with a new line.
- **Shebang Line:** The first line of all files should be exactly `#!/usr/bin/python3`
- **Code Style:** Your code should use `pycodestyle` (version 2.8.0)
- **Imports:** No external modules are allowed.
- **Documentation:** All modules and functions must be documented.
- **Executability:** All your files must be executable.

### Tasks

#### 0. Rotate 2D Matrix

- **Prototype:** `def rotate_2d_matrix(matrix):`
- **Description:** Given an `n x n` 2D matrix, rotate it 90 degrees clockwise. The matrix must be edited in place. You can assume the matrix will have 2 dimensions and will not be empty.
- **Example:**

  ```python
  #!/usr/bin/python3
  """
  Test 0x07 - Rotate 2D Matrix
  """
  rotate_2d_matrix = __import__('0-rotate_2d_matrix').rotate_2d_matrix

  if __name__ == "__main__":
      matrix = [[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]]

      rotate_2d_matrix(matrix)
      print(matrix)

