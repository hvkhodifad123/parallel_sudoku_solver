To run the code, execute the run1.sh file and output will be generated in output.txt file.

To run the code for each case individually, 
    Compile the sudoku-omp.c file           -  gcc sudoku-omp.c -o code -fopenmp -lm
    Now to execute the 'code' file          -  ./code <Filename> <Number of threads>
    
In our code, serial code is run first and then the parallel code is run.

Testcases:

ecase1.txt  - Easiest case 1 (9 x 9 matrix)
ecase2.txt  - Easiest case 2 (9 x 9 matrix)
ecase3.txt  - Easy case (9 x 9 matrix)
mcase.txt   - Medium case (9 x 9 matrix)
hcase.txt   - Hard case (9 x 9 matrix)
16x16.txt   - Case for 16 x 16 matrix
25x25.txt   - Case for 25 x 25 matrix
64x64.txt   - Case for 64 x 64 matrix
impcase.txt - Impossible case (i.e The sudoku is invalid and so has no solution)
