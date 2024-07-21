# N-Queens Solver

This C++ program solves the N-Queens problem using a stack-based approach with backtracking. It finds and prints all possible solutions for placing N queens on an N×N chessboard such that no two queens threaten each other.



1. **Compile and Run**:

   Compile the program using a C++ compiler and run the executable. Follow the prompts to enter the value of N.

2. **Input**:

   - Ensure N is greater than 3 and less than or equal to 20 (`maxNval`).
   - Example: `Enter the value of N (N > 3 and N <= 20): 8`

3. **Output**:

   The program will print all solutions for placing N queens on the chessboard.

## Files

- `NQueens.cpp`: C++ source code for the N-Queens solver.
- `README.txt`: This file, providing instructions and information about the program.

## Code Explanation

- `NQueens.cpp` contains the C++ code for solving the N-Queens problem. It uses a stack-based approach with backtracking to find solutions.

- The program includes the necessary header files (`iostream` and `vector`) and defines a `Stack` structure for stack operations.

- Functions:
  - `isSafe`: Checks if it's safe to place a queen at a specific position on the board.
  - `printBoard`: Prints the chessboard with queens represented as "Q" and empty cells as "*".
  - `solveNQueens`: Solves the N-Queens problem using a stack-based approach with backtracking.
