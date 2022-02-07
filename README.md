<h1 align="center">
  <br>
  <img src="./img/days-of-algo.svg" alt="Days of Algo Logo" width="200" height="200">
  <br>
  Days of Algo
  <br>
</h1>

# Table of contents

[Description](#description) •
[Rules](#rules) •
[Algorithms](#algorithms) •
[Credits](#credits) •

# Description

inspired by [Tomáš Bouda](https://medium.com/@tomas.bouda) and his [100 days of algorithm](https://medium.com/100-days-of-algorithms/100-days-of-algorithms-challenge-41996f7e1ec8) challenge, my attempt on it. Besides my work, my family and other activities this challenge will take me surely longer than 100 days and it can be more or less than 100 algorithms. So be kind.

## Why use Python

The individual challenges should take as less time as possible therefore a high level language such as [Python](https://www.python.org) and all of its available [PIP packages](https://pypi.org/project/pip/) and the fantastic note-like development IDE [Jupyterlab](https://jupyter.org) and [VS Code](https://code.visualstudio.com) as sidekick, the focus isn't on the tools but the algorithms.

# Rules

1. Everything can be a algo
2. Make an effort to code everyday
3. Focus on the challenges not the language
4. Get every help possible
5. Have fun :see_no_evil: :hear_no_evil: :speak_no_evil:

# Algorithms

| Done                    | #Algo | Name                                                                       | Topic      | Algorithm Type       |
| ----------------------  | ----- | -------------------------------------------------------------------------- | ---------- | -------------------- |
| :ballot_box_with_check: |   000 | [Hanoi Tower](./src/000-hanoi-tower.ipynb)                                 | Game       | Recursive            |
| :x:                     |   001 | [Matrix chain multiplication](./src/001-matrix-chain-multiplication.ipynb) | Math       |                      |
| :ballot_box_with_check: |   002 | [Permutations](./src/002-permutations.ipynb)                               | Math       | Recursive            |
| :ballot_box_with_check: |   003 | [Counting 1-bits](./src/003-counting-1bits.ipynb)                          | Digital    | Dynamic Programming  |
| :ballot_box_with_check: |   004 | [Eratosthenes sieve Prime Numbers](./src/004-eratosthenes-sieve.ipynb)     | Math       | Brute Force          |
| :ballot_box_with_check: |   005 | [Binary Addition FSM](./src/005-binary-addition-fsm.ipynb)                 | Digital    | Finite State Machine |
| :x:                     |   006 | [Binary Search](./src/006-binary-search.ipynb)                             | Searching  | Divide and Conquer   |

# Types of Algorithm

## Recursive Algorithm

An algorithms which calls itself with a smaller value as input for solving the current input. In short, it’s an Algorithm that calls itself repeatedly until the problem is solved.

Problems such as the Tower of Hanoi or DFS of a Graph can be easily solved by using these Algorithms.

## Divide and Conquer

In Divide and Conquer algorithms, divide the algorithm into two parts; the first parts divide the problem on hand into smaller subproblems of the same type. Then, in the second part, these smaller problems are solved and then added together (combined) to produce the problem’s final solution.

Merge sorting, and quick sorting can be done with divide and conquer algorithms.

## Dynamic Programming Algorithm

These algorithms work by remembering the results of the past run and using them to find new results. In other words, a dynamic programming algorithm solves complex problems by breaking them into multiple simple subproblems and then it solves each of them once and then stores them for future use.

Fibonacci sequence is a good example for Dynamic Programming algorithms.

## Greedy Algorithm

These algorithms are used for solving optimization problems. In this algorithm, we find a locally optimum solution (without any regard for any consequence in future) and hope to find the optimal solution at the global level.

The method does not guarantee that we will be able to find an optimal solution.

The algorithm has 5 components:

The first one is a candidate set from which we try to find a solution.
A selection function that helps choose the best possible candidate.
A feasibility function that helps in deciding if the candidate can be used to find a solution.
An objective function that assigns value to a possible solution or to a partial solution
Solution function that tells when we have found a solution to the problem.
Huffman Coding and Dijkstra’s algorithm are two prime examples where the Greedy algorithm is used.

These algorithms are used for solving optimization problems. In this algorithm, we find a locally optimal solution and hope to find the optimal solution on a global scale.

The method does not guarantee that we can find an optimal solution.

The algorithm consists of 5 components:
* The first component is a candidate set from which we try to find a solution.
* A selection function that helps to choose the best possible candidate.
* A feasibility function that helps decide if the candidate can be used to find a solution.
* An objective function that assigns a value to a possible solution or partial solution.
* Solution function that indicates when we have found a solution to the problem.

Huffman coding and Dijkstra's algorithm are two main examples of the use of the Greedy algorithm.

## Brute Force Algorithms

A brute force algorithm blindly iterates all possible solutions to search one or more than one solution that may solve a function. Think of brute force as using all possible combinations of numbers to open a safe.

## Backtracking Algorithms

Backtracking is a technique to find a solution to a problem in an incremental approach. It solves problems recursively and tries to solve a problem by solving one piece of the problem at a time. If one of the solutions fail, we remove it and backtrack to find another solution.

In other words, a backtracking algorithm solves a subproblem, and if it fails to solve the problem, it undoes the last step and starts again to find the solution to the problem.

For example Sudoku solver  or N-Queen Problems can be solved with backtracking algorithms.

# Credits

* [Tomáš Bouda](https://medium.com/@tomas.bouda)
