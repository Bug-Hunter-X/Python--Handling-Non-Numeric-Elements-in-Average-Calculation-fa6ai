# Python: Handling Non-Numeric Elements in Average Calculation

This repository demonstrates a common error in Python when calculating the average of a list of numbers: not handling non-numeric elements.  The `bug.py` file contains the erroneous code, while `bugSolution.py` provides a corrected version.

The bug is that the original code does not check the data type of elements in the input list before performing the sum operation, leading to a TypeError if non-numeric values are present. The improved version uses a type check and handles the error gracefully.