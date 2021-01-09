# Monster Sudoku

## How to Run (Using Command Line):
* This project is implemented with Python 3.7</p>
* Windows (cmd or Powershell) / Mac (Terminal) / Linux (Terminal): python3 <strong>Main.py</strong>

## Variable Selection Heuristics:
1. Minimum Remaining Value (MRV)</p>
2. Minimum Remaining Value with Degree heuristic as a tie-breaker (MAD)

## Value Selection Heuristics:
1. Least Constraining Value (LCV). Has a specific tie-breaking mechanism.
  
## Consistency Checks:
1. Forward Checking</p>
2. Norvig’s Check (NOR)</p>

## What is Monster Sudoku 
> Monster Sudoku (or Mega Sudoku) is a puzzle that follows the rules of Sudoku and is played on a NxN grid, N being any positive integer including N > 9.</p>
> The numbers that fill each square are selected from the first N positive integers.</p>
> For display purposes, they are shown as 1, 2, ..., 9, A, B, ..., Z so that each token takes up exactly one column when printed.</p>

## <strong>Four</strong> Parameters:
1. N = the length of one side of the NxN grid, also the number of distinct tokens</p>
2. P = the number of rows in each block, also the number of block columns.</p>
3. Q = the number of columns in each block, also the number of block rows.</p>
4. M = the number of values filled in from the start.</p>
  
## Difficulty</p>
* Easy: P = Q = 3, N = 9 with 7 given values</p>
* Intermediate: P = 3, Q = 4, N = 12 with 11 given values</p>
* Hard: P = Q = 4, N = 16 with 20 given values</p>
* Expert: P = Q = 5, N = 25 with 30 given values</p>
