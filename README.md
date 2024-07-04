# Sorting Algorithms in C

## Introduction

This repository contains implementations of various sorting algorithms in the C programming language. Sorting algorithms are fundamental to computer science and are used to arrange elements in a list or array in a certain order, typically ascending or descending.

## Table of Contents

- [Introduction](#introduction)
- [Implemented Algorithms](#implemented-algorithms)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Implemented Algorithms

- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort
- Heap Sort
- Radix Sort

## Getting Started

### Prerequisites

To compile and run the sorting algorithms, you need to have a C compiler installed on your system. For example, you can use `gcc` (GNU Compiler Collection).

### Installation

Clone the repository to your local machine using the following command:

```sh
git clone https://github.com/emmanuelj-unit/sorting_algorithms.git
```

Navigate to the project directory:

```sh
cd sorting-algorithms-c
```

### Usage

To compile and run a specific sorting algorithm, use the following commands:

1. **Bubble Sort**:
    ```sh
    gcc bubble_sort.c -o bubble_sort
    ./bubble_sort
    ```

2. **Insertion Sort**:
    ```sh
    gcc insertion_sort.c -o insertion_sort
    ./insertion_sort
    ```

3. **Selection Sort**:
    ```sh
    gcc selection_sort.c -o selection_sort
    ./selection_sort
    ```

4. **Merge Sort**:
    ```sh
    gcc merge_sort.c -o merge_sort
    ./merge_sort
    ```

5. **Quick Sort**:
    ```sh
    gcc quick_sort.c -o quick_sort
    ./quick_sort
    ```

6. **Heap Sort**:
    ```sh
    gcc heap_sort.c -o heap_sort
    ./heap_sort
    ```

7. **Radix Sort**:
    ```sh
    gcc radix_sort.c -o radix_sort
    ./radix_sort
    ```

Each program will prompt you to enter an array of integers, and then it will display the sorted array.

## Examples

### Example Input

For an array with the following elements:
```
5 3 8 4 2
```

### Example Output

For Bubble Sort, the output will be:
```
Sorted array: 2 3 4 5 8
```

## Contributing

Contributions are welcome! If you have any improvements or new algorithms to add, feel free to open a pull request. Please ensure your code follows the repository's coding standards and includes appropriate comments and documentation.

#