# Sudoku Solver

## Overview
This is a **Sudoku Solver** implemented in **Java**.  
It uses **backtracking** to solve a standard 9x9 Sudoku puzzle.  
The program fills empty cells (represented by '.') with numbers from 1 to 9 while satisfying all Sudoku rules.

## Features
- Solves any valid 9x9 Sudoku puzzle  
- Uses **backtracking algorithm** for solving  
- Validates each move according to Sudoku rules  
- Prints the solved Sudoku board in a readable format  

## How It Works
1. **Check Safety**: The `isSafe` method checks if placing a number in a cell is valid (row, column, and 3x3 subgrid).  
2. **Backtracking**: The `helper` method tries all possible numbers for each empty cell recursively.  
3. **Solve Sudoku**: The `solveSudoku` method starts the solving process from the top-left cell (0,0).  
4. **Print Board**: After solving, the board is printed row by row.

## Technologies Used
- **Java** – Programming language for implementation  
- **Console** – For input/output  

## Installation / Usage
1. Clone the repository or download the ZIP:  
```bash
git clone <https://github.com/roligupta123/sudoku_game.git>
```

## Compile the Java program:
```bash
javac suduku.java
```

## Run the program:
```bash
java suduku
```



