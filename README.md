# Sudoku
CM50263 Artificial Intelligence

I chose to implement a backtracking depth-first algorithm, which allows the program to check stuff using bitwise operators, to solve sudoku with a medium difficulty level. The logic is to define sudoku_solver at the beginning, to check if the sudoku has solution or not, define both possibilities, divide the sudoku into arrays(structures for rows, columns, and the nine sub-squares, and further define the number assign(between 1 and 9), valid move, value check, seven defs in total.
 
 
Code details explanation:
1. X means row, y means col. While check if it’s valid move, need to check Xs, Ys and all 3*3 blocks, add 3*3 blocks check functions can get better solve result
2. Use np.unique to find the unique elements of an array, this function works better/can solve more sudoku than np.array


References
DELAHAYE, J., 2006. The Science Behind Sudoku. [online] Cs.virginia.edu. Available at: http://www.cs.virginia.edu/~robins/The_Science_Behind_SudoKu.pdf
