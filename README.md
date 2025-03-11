Problem Statement: Sudoku Solver
Objective:
Write a program to solve a given Sudoku puzzle using the backtracking algorithm. The program should be able to take a partially filled 9x9 Sudoku grid, solve it, and output the solved Sudoku grid. Additionally, track and display the stages of the algorithm as it reaches the solution.

Problem Description:
Sudoku is a number puzzle that consists of a 9x9 grid. The grid is divided into nine 3x3 subgrids, and the objective is to fill the grid with digits from 1 to 9 such that:

Each row contains each digit exactly once.
Each column contains each digit exactly once.
Each 3x3 subgrid contains each digit exactly once.
Some cells in the grid are already filled with numbers, and the remaining cells need to be filled according to the above rules.

Your task: Write a Python program that:

Solves the Sudoku puzzle using backtracking.
Tracks and outputs:
The initial state of the Sudoku grid.
One intermediate stage of the solution process after placing the first valid number.
The final state after the puzzle is solved.
Tracks how many stages it takes to reach the intermediate state (first valid number placement) and how many stages it takes to complete the puzzle from the intermediate state to the final solution.
