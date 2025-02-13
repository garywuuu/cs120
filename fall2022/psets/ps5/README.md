# Problem Set 5

## Overview

This problem set explores two algorithms for solving 3-coloring:
- Exhaustive search
- Augmentation of 2-coloring algorithm with independent sets (covered in Sender Receiver Exercise)

We have implemented exhaustive search for you as a benchmark. You will implement the BFS 2-coloring algorithm in part 1a and the ISET + BFS 3-coloring algorithm in parts 1b and 1c. In 1d, you will compare the performance of these algorithms.

*Make sure to pull from the course source often or check Ed for updates. We hope to release a perfect problem set but sometimes we add to the problem set to make things easier or fix obscure bugs.*

## Instructions

**Problem 1a**: First, implement the O(n+m)-time algorithm for 2-coloring that we covered in class, verifying its correctness by running `python3 -m ps5_tests 2`.

**Problem 1b**: Implement is_independent_set, which checks if a given subset of nodes is an independent set.

**Problem 1c**: Implement the O(1.89^n)-time algorithm for 3-coloring that you studied in the Sender Receiver Exercise, also verifying its correctness by running `python3 -m ps5_tests 3`.

**Problem 1d**: Run the experiments we provided in `ps5_experiments.py` and compare the efficiency of the two coloring algorithms in your writeup.

**Conclusion**: If your work passes the local tests and you answer 1d, you should be in good shape to get full marks for this problem.
You can check that you pass all tests by running `python3 -m ps5_tests`.

## Running the Code

The problem set includes some starter code in `ps5.py`. To run the code, type in your terminal:

```bash
python3 -m ps5
```

## Running the Included Tests

The problem set also includes some tests for you to test your code.

To run the tests, type in your terminal:

```bash
python3 -m ps5_tests 2
```

```bash
python3 -m ps5_tests 3
```

```bash
python3 -m ps5_experiments
```