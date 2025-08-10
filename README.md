# Matrix (2D Arrays) and it's Operations in C++

Aim : To study and implement operations on 2D arrays (matrices) in C++.

Tools: VS Code

# Theory:

## What is a 2D Array?

A two-dimensional array (2D array) in C++ is a collection of elements stored in rows and columns, like a table or matrix. It is used to represent mathematical matrices or tabular data.It stores data in a grid-like structure, where each element can be accessed by two indices — one for the row and one for the column.

# Key points:

* Declared as `data_type array_name[rows][columns];`

* Each element is accessed using `array[i][j]`

* Useful for matrix operations like addition, multiplication, transpose, and diagonal summation.

# Applications of 2D Arrays :

## 1. Mathematical Matrices:
* Used to store and manipulate matrices in linear algebra.
* Enables operations like addition, subtraction, multiplication, transpose, determinant, etc.

## 2. Tabular Data (Tables & Grids):
* Represents data in rows and columns, like a spreadsheet.

## 3. Image Processing:
* A grayscale image can be represented as a 2D array of pixels (integers).

## 4. Game Development:
* Games that use grids (like Tic Tac Toe, Chess, Sudoku, Minesweeper) can use 2D arrays for the game board.


# Program Explanations :

## 1. 2D Array Input and Display:

This program demonstrates how to take input-output in a matrix and display it in matrix form 2D array handling.

Algorithm:

1. Define matrix of size 3x3.
   
2. Input matrix elements.
   
3. Display matrix elements in row-column format.

## 2. Matrix Addition:

This program adds two matrices of the same dimensions by summing their corresponding elements and stores in other matrix, if dimensons are not same then it will prompt user .

Algorithm:

1. Input dimensions of both matrices.

2. Input elements of both matrices.

3. Initialize result matrix.

4. Loop through all elements and add corresponding elements.

5. Display the resultant matrix.

## 3. Matrix Multiplication:

This program multiplies two matrices where columns of matrix 1 match rows of matrix 2 and store it in other matrix if dimensions doesn’t match so it will prompt user.

Algorithm:

1. Input rows and columns for both matrices.

2. Check if column count of matrix 1 equals row count of matrix 2.

3. Input elements of both matrices.

4. Initialize result matrix to zero.

5. Multiply for each element of result, sum products of row elements of matrix 1 and column elements of matrix 2.

6. Display the result matrix.

## 4. Matrix Transpose:

This program calculates the sum of diagonal elements in a square matrix (same number of rows and columns).

Algorithm:

1. Input rows and columns.

2. Input matrix elements.

3. Create transpose matrix with swapped dimensions.

4. For each element (i,j), assign to transpose[j][i].

5. Display the transposed matrix.

## 5. Sum of Diagonal Elements of a Matrix:

This program checks if two matrices are exactly equal in both size and element values, if not user will be prompted appropriately.

Algorithm:

1. Input the number of the rows and columns.

2. Check if the matrix is square (rows == cols).

3. Input the matrix elements if it is a square matrix.

4. Initialize a sum variable to 0.

5. Loop through each row i and add the element at matrix[i][i] to the sum.

6. Output the sum.

# Conclusion:

In this experiment, We performed matrix input, display, addition, multiplication, diagonal sum, transpose, and row comparison using nested loops and 2D arrays. This helped us understand how to use two-dimensional arrays effectively for mathematical and data-based operations. We also learned the logic behind row-column traversal, element-wise operations, and condition checking in matrices. The experiment enhanced our logical thinking and improved our C++ programming skills for real-life matrix problems.
