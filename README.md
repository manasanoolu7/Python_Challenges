
# Challange:

So given a string with embedded newlines like:

    9 8 7 5 3 2 6 6 7

representing this matrix:

    0  1  2
  |---------
0 | 9  8  7
1 | 5  3  2
2 | 6  6  7

your code should be able to spit out:

    A list of the rows, reading each row left-to-right while moving top-to-bottom across the rows,
    A list of the columns, reading each column top-to-bottom while moving from left-to-right.

The rows for our example matrix:

    9, 8, 7
    5, 3, 2
    6, 6, 7

And its columns:

    9, 5, 6
    8, 3, 6
    7, 2, 7

# Requirements:

numpy library

# IDE:

Jupyter Notebook


# How

**Step1:** Class *Matrix_Spit()* that takes input string with shapes(dimensions).

**Step2:** Three methods called convert_matrix,split_rows,split_columns are defined in the class.

**a.** *convert_matrix()* that converts input string to matrix by using numpy.arange() and reshapes to input dimensions.

**b.** *split_rows()* takes matrix as input and read each row and stores in the list.

**c.** *split_columns()* takes matrix as input and perform transpose to get columns. Each column is read and stored in the column list.

**Step3:** each row and column from the respective lists  are fed to *join()* to add ',' to the elements.Followed by extracting the numeric values by slice.




*This program works for **dynamic input**


