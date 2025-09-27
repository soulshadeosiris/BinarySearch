# Binary Search

This repository contains an implementation of the Binary Search algorithm in Python.

## Description
Binary Search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing the search interval in half. If the value of the search key is less than the item in the middle of the interval, the algorithm continues on the lower half. Otherwise, it continues on the upper half. This process continues until the value is found or the interval is empty.

## File Structure
- `binary_search.py` — Python file with the implementation of the binary search algorithm.

## Usage
1. Make sure you have Python installed on your system.
2. Run the script or import the function from `binary_search.py` in your project.

## Example
```python
from binary_search import binary_search

arr = [1, 3, 5, 7, 9, 11]
target = 7
result = binary_search(arr, target)
if result != -1:
    print(f"Element found at index {result}")
else:
    print("Element not found")
```

## License
This project is licensed under the MIT License.