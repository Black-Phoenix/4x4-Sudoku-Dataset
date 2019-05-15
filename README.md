#Data set of 4x4 Sudoku puzzles and solutions.

##Data generation
The sudoku generation was done by referring to a code by Arel Cordero, who wrote and shared this Sudoku generation code. https://www.ocf.berkeley.edu/~arel/sudoku/main.html.
It took approximately 2 hours to generate 1 million games and its solutions. The data is stored in two a comma-separated values files


In each line, a Sudoku quiz and its corresponding solution are separated by a comma. Blanks in the quiz are replaced with zeros.

There are 2 data sets
1) 4x4_sudoku_unique_puzzles.csv
	This data set has a million unique puzzles. However note that the solutions to these puzzles may not be unique.
	
2) 4x4_sudoku_unique_solution.csv
	This data set has 288 puzzles. Each of these puzzles have a unique solution. This is based on the fact that there are only 288 possible ways of arranging a 4x4 Sudoku puzzle (http://pi.math.cornell.edu/~mec/Summer2009/Mahmood/Four.html)