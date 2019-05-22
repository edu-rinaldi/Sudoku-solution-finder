# Sudoku Solution Finder
This is a  **backtracking** algorithm for finding a solution to an NxN Sudoku.

The main function of the project is `risolvi_sudoku(schema)` , which it takes only one argument and it is the matrix (list of lists) representation of the sudoku table.

Example:
```python
schema = [
[0,0,5,3,0,0,0,0,0],
[8,0,0,0,0,0,0,2,0],
[0,7,0,0,1,0,5,0,0],
[4,0,0,0,0,5,3,0,0],
[0,1,0,0,7,0,0,0,6],
[0,0,3,2,0,0,0,8,0],
[0,6,0,5,0,0,0,0,9],
[0,0,4,0,0,0,0,3,0],
[0,0,0,0,0,9,7,0,0]
]
```

For running the code you have to **change** this block:
```python
if  __name__  ==  "__main__":
	risolvi_sudoku(schema16_2)
```

