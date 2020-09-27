# Monster-Sudoku-AI

Variable Selection Heuristics:
  Minimum Remaining Value (MRV)
  Minimum Remaining Value with Degree heuristic as a tie-breaker (MAD)
Value Selection Heuristics:
  Least Constraining Value (LCV). Has a specific tie-breaking mechanism.
Consistency Checks:
  Forward Checking (FC)
  Norvig’s Check (NOR)

Monster Sudoku (or Mega Sudoku) is a puzzle that follows the rules of Sudoku and is played on a NxN grid, N being any positive integer including N > 9.
The numbers that fill each square are selected from the first N positive integers.
For display purposes, they are shown as 1, 2, ..., 9, A, B, ..., Z so that each token takes up exactly one column when printed.
Monster Sudoku puzzles are described by four parameters:
  N = the length of one side of the NxN grid, also the number of distinct tokens
  P = the number of rows in each block, also the number of block columns.
  Q = the number of columns in each block, also the number of block rows.
  M = the number of values filled in from the start.
  

Each difficulty has a different board dimension and number of values given initially:
  Easy: P = Q = 3, N = 9 with 7 given values
  Intermediate: P = 3, Q = 4, N = 12 with 11 given values
  Hard: P = Q = 4, N = 16 with 20 given values
  Expert: P = Q = 5, N = 25 with 30 given values
