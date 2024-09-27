# 2D-matrices
Experiment 8

# AIM

To study and implement 2 Dimensional arrays in C++

# Theory

A 2D array is a data structure that with a grid, where each element is identified by two indices: a row index and a column index.

int matrix[3][4] = {
    {1, 2, 3, 4},
    {5, 6, 7, 8},
    {9, 10, 11, 12}
};
## Features of 2D array:

Structure: A 2D array is essentially an array of arrays, where each element of the outer array is another array representing a row in the matrix.
Indexing:
Elements in a 2D array are accessed using two indices.
Contiguous Memory:
In C++, a 2D array is stored in memory as a continuous block of memory.
Operations:
Various operations can be performed on 2D arrays, including addition, subtraction, and multiplication (in the case of matrices).

## Uses of 2D Arrays:

Used in applications including computer graphics, image processing.
Used in scientific simulations, spreadsheets.
Used in mathematical representation of matrix. eg-
1	2	3
4	5	6
7	8	9
## Algorithm

Display the Matrices.

Start

Input:

Ask user to enter the number of rows (r).

Prompt user to enter the number of columns (c).

Initialize:

Create a 2D array arr[r][c].

Input Elements:

For each row i from 0 to r-1:

For each column j from 0 to c-1:

Ask user to enter the element at position (i+1, j+1).

Store the entered value in arr[i][j].

Display Matrix:

For each row i from 0 to r-1:

For each column j from 0 to c-1:

Print arr[i][j] followed by a space.

Print a newline after each row.

End

Addition of Diagonal of Matrices.

Start

Initialize:

Define r (number of rows) to 3.

Define c (number of columns) to 3.

Define a 2D array a with the following elements:

1 2 3
5 7 4
5 9 1

Set sum to 0.

Check matrix:

If r is equal to c (i.e., the matrix is square):

Display Matrix:

For each row i from 0 to r-1:

For each column j from 0 to c-1:

Print the element a[i][j] followed by a space.

Print a newline after each row.

Sum of Diagonals:

For each row i from 0 to r-1:

For each column j from 0 to c-1:

If i is equal to j (i.e., the element is on the main diagonal):

Add a[i][j] to sum.

Display Result:

Print "The sum of diagonals is: " followed by the value of sum.

Else if r is not equal to c:

Print "Input should be square matrix."

End

Multiplication of Matrices.

Input Matrix Dimensions:

Matrix A: Number of rows (rA) and columns (cA).

Matrix B: Number of rows (rB) and columns (cB).

Check Matrix Multiplication Validity:

Ensure that the number of columns in Matrix A (cA) matches the number of rows in Matrix B (rB). If not, matrix multiplication cannot be performed.

Allocate Memory for Matrices:

Create Matrix A of size rA x cA.

Create Matrix B of size rB x cB.

Create Matrix C for the result of size rA x cB and initialize it to zero.

Input Matrix Elements:

Input elements for Matrix A.

Input elements for Matrix B.

Perform Matrix Multiplication:

Initialize all elements of Matrix C to 0.

For each element C[i][j] in the resulting matrix:

Compute C[i][j] as the sum of the products of corresponding elements from the row i of Matrix A and column j of Matrix B.

Output the Result:

Display the resultant Matrix C.
