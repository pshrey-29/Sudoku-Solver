-> Sudoku Solver
It is a sudoku solver made using HTML CSS and javascript. It can generate sudoku puzzle and solve it. 

-> Algorithm
We start at the first empty square, try a number, and check the row, column, and nearest 3x3 square for a match. If there is no match, the number is currently valid, so move to the next square and try a new number. If you try numbers 1-9 and find no valid numbers, go back to the previous square and increment it by one until you either exceed 9 or you find a new possible valid number. Keep following this same plan, sliding forward and backward through the empty squares until you arrive at a solution.
This is a backtracking algorithm. The basic idea being that you incrementally build a solution and discard it once you realize that it’s not viable.

- New Puzzle: It will generate a new puzzle 
- Solve: This will solve the Sudoku
