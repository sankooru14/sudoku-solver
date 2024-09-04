# Sudoku Solver

## Overview

This project is a fully functional Sudoku Solver implemented using HTML, CSS, and JavaScript. The application allows users to input Sudoku puzzles and solve them in real-time. It showcases your ability to work with front-end and back-end technologies, manage data, and implement algorithms.

## Features

- **Interactive User Interface:** 
  - Developed using HTML and styled with CSS for a clean and responsive design.
  - Users can input their Sudoku puzzles directly on the board using an editable grid.

- **Real-Time Puzzle Solving:**
  - The solver instantly processes the input and solves the puzzle using a backtracking algorithm.
  - The solution is displayed on the board with a single click of the "Solve!" button.

- **Input Validation:**
  - Ensures only valid numbers (1-9) can be entered in the cells.
  - Invalid entries are automatically cleared to maintain puzzle integrity.

- **Clear Functionality:**
  - Provides a "Clear board" button to reset the puzzle board, allowing users to start fresh without refreshing the page.

## Technology Stack

- **Front-End:**
  - **HTML5 & CSS3:** Used to create a clean, responsive UI with an intuitive layout.
  - **JavaScript:** Handles user input, real-time updates, and the puzzle-solving algorithm.

- **Back-End (Logic):**
  - **JavaScript:** Implements the Sudoku-solving algorithm using recursion and backtracking, ensuring efficient puzzle resolution.
  - **Modular Design:** The logic is encapsulated in a `SudokuSolver` module, which is easily testable and maintainable.

## Sudoku Solving Algorithm

The core algorithm is a recursive backtracking approach that attempts to fill the Sudoku grid while ensuring all constraints (row, column, and 3x3 box uniqueness) are met. If a conflict is detected, the algorithm backtracks and tries a different number.

### Steps:
1. **Input Validation:** The algorithm first checks if the initial board configuration is valid.
2. **Recursive Solve:** It identifies the next empty cell and tries all possible numbers (1-9). If a valid number is found, it moves to the next cell. If no valid number is found, it backtracks to the previous cell.
3. **Solution Display:** Once a solution is found, it is displayed on the Sudoku grid.

## How to Use

1. **Input Puzzle:**
   - Click on any cell in the Sudoku grid to enter a number (1-9). Leave cells empty for unsolved positions.
2. **Solve Puzzle:**
   - Click the "Solve!" button to solve the puzzle. The solution will automatically populate the grid.
3. **Clear Puzzle:**
   - Click the "Clear board" button to reset the grid and start over.

## File Structure

- **index.html:** The main HTML file containing the Sudoku board layout and buttons.
- **sudoku.js:** The JavaScript file containing the Sudoku-solving algorithm and event handlers for user interaction.
- **styles.css (inline):** Embedded CSS for styling the application.

## Learning Outcomes

- **Algorithm Design:** Developed a deep understanding of recursive algorithms and backtracking techniques.
- **UI Development:** Gained experience in creating interactive and user-friendly web applications using HTML, CSS, and JavaScript.
- **Modular Programming:** Applied best practices in modular design, ensuring the application logic is maintainable and testable.

## Conclusion

This project demonstrates a strong grasp of both front-end and back-end development, along with problem-solving skills in implementing algorithms. The Sudoku Solver is a practical example of turning complex logic into a user-friendly application.
