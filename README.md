
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

Used class that takes input string with shapes. Three methods called convert_matrix,split_rows,split_columns are defined in the class to perform the task for generating a matrix followed by row and columns extraction.

*This program works for dynamic input


