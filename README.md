# Sorting Algorithm

A simple collection of sorting algorithm implementations in Python, implemented as Jupyter notebooks for learning and experimentation.

## Overview

This repository demonstrates two fundamental sorting techniques:

- Insertion Sort
- Merge Sort

The goal is to provide beginner-friendly examples of how common sorting algorithms work and how they can be implemented in Python.

## Repository Structure

```text
Sorting_Algorithm/
├── Insertion_Sort.ipynb
├── Merge_Sort.ipynb
└── README.md
```

## Included Algorithms

### 1. Insertion Sort
File: `Insertion_Sort.ipynb`

Insertion sort builds the final sorted array one item at a time. It works well for small datasets and is easy to understand.

Key idea:
- Take one element from the unsorted part
- Insert it into the correct position in the sorted part
- Repeat until the whole array is sorted

Time complexity:
- Best case: O(n)
- Average case: O(n²)
- Worst case: O(n²)

### 2. Merge Sort
File: `Merge_Sort.ipynb`

Merge sort is a divide-and-conquer algorithm. It splits the array into halves, sorts each half recursively, and then merges them back together.

Key idea:
- Split the array into two halves
- Recursively sort each half
- Merge the sorted halves

Time complexity:
- Best case: O(n log n)
- Average case: O(n log n)
- Worst case: O(n log n)

## Example Usage

The notebooks include simple examples like:

```python
Array = [5, 4, 3, 2, 1]
print(insertion_sort(Array))
```

```python
Array = [9, 8, 7, 6, 5, 4, 3, 2, 1]
print(merge_sort(Array))
```

Output:

```python
[1, 2, 3, 4, 5]
[1, 2, 3, 4, 5, 6, 7, 8, 9]
```

## Technologies Used

- Python
- Jupyter Notebook

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/E2jie/Sorting_Algorithm.git
```

2. Open the notebooks in Jupyter Notebook or VS Code.

3. Run the cells to see how each sorting algorithm works.

## Learning Goals

This project is intended for:

- learning basic sorting algorithms
- understanding algorithmic thinking
- practicing Python implementation of common data structures and algorithms

## Notes

This repository is a beginner-focused project and is designed to make sorting algorithms easy to follow and experiment with.

## Author

Created by E2jie.
