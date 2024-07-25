# UTF-8 Validation

## Project Overview

The goal of this project is to validate whether a given dataset represents a valid UTF-8 encoding. This involves applying bitwise operations and understanding the UTF-8 encoding scheme. The dataset will be represented as a list of integers, each corresponding to one byte of data.

## Concepts Covered

- **Bitwise Operations**: Learn to manipulate bits using operations like AND (`&`), OR (`|`), XOR (`^`), NOT (`~`), and bit shifts (`<<`, `>>`).
  - [Python Bitwise Operators](https://docs.python.org/3/library/operator.html#bitwise-operations)
  
- **UTF-8 Encoding Scheme**: Understand how characters are encoded into one or more bytes and the patterns that represent valid UTF-8 encoded characters.
  - [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
  - [Characters, Symbols, and the Unicode Miracle](https://unicode.org/standard/WhatIsUnicode.html)
  - [The Absolute Minimum Every Software Developer Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/11/19/encoding-utf-8/)

- **Data Representation**: Work with data at the byte level and handle the least significant bits (LSB) of integers to simulate byte data.
  - [Python Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)

- **List Manipulation**: Iterate through lists, access list elements, and use list comprehensions.
  - [Python Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)

- **Boolean Logic**: Apply logical operations to make decisions within the program.

## Requirements

- **Editors**: Allowed editors are `vi`, `vim`, and `emacs`.
- **Python Version**: All files should be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3.
- **File Formatting**:
  - All files should end with a new line.
  - The first line of all files must be `#!/usr/bin/python3`.
- **Code Style**: Follow the PEP 8 style guide (version 1.7.x).
- **File Permissions**: All files must be executable.
- **Documentation**: A `README.md` file at the root of the project folder is mandatory.

## Task

### 0. UTF-8 Validation

**Mandatory**

Write a method to determine if a given data set represents a valid UTF-8 encoding.

- **Prototype**: `def validUTF8(data) -> bool`
- **Return**: Return `True` if data is a valid UTF-8 encoding, else return `False`.

**Details**:
- A character in UTF-8 can be 1 to 4 bytes long.
- The dataset can contain multiple characters.
- The data is represented by a list of integers, with each integer representing one byte of data.

**Example**:

```python
# Example test script

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))  # True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # True

data = [229, 65, 127, 256]
print(validUTF8(data))  # False
