
# Lockboxes

## Project Overview
This project involves developing a solution to determine if all boxes can be opened. Each box contains keys to other boxes, and the goal is to see if you can unlock all of them starting from the first box.

### Must Know
To successfully complete this project, a solid understanding of the following concepts is essential:

1. **Lists and List Manipulation**
   - Understanding how to work with lists, including accessing elements, iterating over lists, and modifying lists dynamically.
   - [Python Lists (Python Official Documentation)](https://docs.python.org/3/tutorial/datastructures.html)

2. **Graph Theory Basics**
   - Knowledge of graph theory, particularly traversal algorithms like Depth-First Search (DFS) or Breadth-First Search (BFS), can be very helpful.
   - [Graph Theory (Khan Academy)](https://www.khanacademy.org/computing/computer-science/algorithms#graph-representation)

3. **Algorithmic Complexity**
   - Understanding the time and space complexity of your solution is crucial for writing efficient algorithms.
   - [Big O Notation (GeeksforGeeks)](https://www.geeksforgeeks.org/analysis-of-algorithms-set-1-asymptotic-analysis/)

4. **Recursion**
   - Some solutions might require a recursive approach to traverse through the boxes and keys.
   - [Recursion in Python (Real Python)](https://realpython.com/python-recursion/)

5. **Queue and Stack**
   - Knowledge of using queues and stacks is crucial if implementing BFS or DFS algorithms.
   - [Python Queue and Stack (GeeksforGeeks)](https://www.geeksforgeeks.org/queue-in-python/)

6. **Set Operations**
   - Using sets for keeping track of visited boxes and available keys can optimize the search process.
   - [Python Sets (Python Official Documentation)](https://docs.python.org/3/tutorial/datastructures.html#sets)

### Additional Resources
- Mock Technical Interview

### Requirements
- **General**
  - Allowed editors: `vi`, `vim`, `emacs`
  - All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python3 (version 3.4.3)
  - All files should end with a new line
  - The first line of all files should be exactly `#!/usr/bin/python3`
  - A `README.md` file at the root of the project folder is mandatory
  - Code should be documented
  - Code should use the PEP 8 style (version 1.7.x)
  - All files must be executable

### Tasks

#### 0. Lockboxes
**Mandatory**

You have `n` number of locked boxes in front of you. Each box is numbered sequentially from 0 to `n-1` and each box may contain keys to the other boxes.

Write a method that determines if all the boxes can be opened.

- **Prototype:** `def canUnlockAll(boxes)`
- `boxes` is a list of lists
- A key with the same number as a box opens that box
- You can assume all keys will be positive integers
- There can be keys that do not have boxes
- The first box `boxes[0]` is unlocked
- Return `True` if all boxes can be opened, else return `False`

```python
#!/usr/bin/python3

canUnlockAll = __import__('0-lockboxes').canUnlockAll

boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))  # True

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))  # True

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))  # False
```