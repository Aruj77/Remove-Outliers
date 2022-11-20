# Remove-Outliers
In this file you will find a function which will help you in cleaning data by removing all the unwanted outliers.


Outliers - These are the values that are not needed in the dataset as the are very far away from the range.

For finding these outliers we need to find:
  q1 = 25%tile
  q3 = 75%tile
  iqr = q3-q1
  lower fence = q1 - 1.5*iqr
  upper fence = q3 + 1.5*iqr
