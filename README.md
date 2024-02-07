## Sudoku Solver

This project is a Sudoku Solver implemented in JavaScript, utilizing the backtracking algorithm. It serves as a demonstration of the developer's skills in algorithmic problem-solving and web development.

### Overview

Sudoku is a popular puzzle game where the objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids that compose the grid contain all of the digits from 1 to 9. This solver allows users to input a partially filled Sudoku grid and solves it using a backtracking algorithm.

### How it Works

The solver employs a recursive backtracking approach to find the solution to the Sudoku puzzle. It systematically fills in cells with valid numbers and backtracks whenever it reaches a dead end, i.e., when it cannot find a valid number to place in a cell. The algorithm ensures that the solution meets the rules of Sudoku by validating each row, column, and 3x3 subgrid.

### Files

- **index.html**: The HTML file containing the structure of the web page. It includes the Sudoku grid and buttons for solving and clearing the board.
- **sudoku.js**: The JavaScript file containing the implementation of the Sudoku solver. It defines functions for solving the puzzle, validating the board, and converting between string representations of the board and arrays.

### Usage

To use the Sudoku solver, simply visit the [GitHub Pages link](https://bunyod-suvonov.github.io/Sudoku-Solver/) and input your partially filled Sudoku grid into the provided table. Click the "Solve!" button to see the solution, or click "Clear board" to reset the grid.

### Testing

This project includes a testing mode that exposes additional functions for unit testing purposes. These functions are not intended for public use but aid in ensuring the correctness of the solver's implementation.

Explore the [GitHub Pages](https://bunyod-suvonov.github.io/Sudoku-Solver/) to see the Sudoku solver in action!
