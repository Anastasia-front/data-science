# TASKS

## intro_data_science
<details>
  <summary>Click to expand/collapse</summary>
  **PART 1:** 
1. Create a one-dimensional array (vector) with the first 10 natural numbers and print its values.
2. Create a two-dimensional array (matrix) of size 3x3, fill it with zeros, and print its values.
3. Create a 5x5 array, fill it with random integers in the range from 1 to 10, and print its values.
4. Create a 4x4 array, fill it with random floating-point numbers in the range from 0 to 1, and print its values.
5. Create two one-dimensional arrays of size 5, fill them with random integers in the range from 1 to 10, and perform element-wise addition, subtraction, and multiplication.
6. Create two vectors of size 7, fill them with arbitrary numbers, and find their dot product.
7. Create two matrices of size 2x2 and 2x3, fill them with random integers in the range from 1 to 10, and multiply them together.
8. Create a 3x3 matrix, fill it with random integers in the range from 1 to 10, and find its inverse matrix.
9. Create a 4x4 matrix, fill it with random floating-point numbers in the range from 0 to 1, and transpose it.
10. Create a 3x4 matrix and a vector of size 4, fill them with random integers in the range from 1 to 10, and multiply the matrix by the vector.
11. Create a 2x3 matrix and a vector of size 3, fill them with random floating-point numbers in the range from 0 to 1, and multiply the matrix by the vector.
12. Create two matrices of size 2x2, fill them with random integers in the range from 1 to 10, and perform element-wise multiplication.
13. Create two matrices of size 2x2, fill them with random integers in the range from 1 to 10, and find their product.
14. Create a 5x5 matrix, fill it with random integers in the range from 1 to 100, and find the sum of its elements.
15. Create two matrices of size 4x4, fill them with random integers in the range from 1 to 10, and find their difference.
16. Create a 3x3 matrix, fill it with random floating-point numbers in the range from 0 to 1, and find a column vector containing the sum of elements of each row of the matrix.
17. Create a 3x4 matrix with arbitrary integers and create a matrix with the squares of these numbers.
18. Create a vector of size 4, fill it with random integers in the range from 1 to 50, and find a vector with the square roots of these numbers.

**PART 2** (additional, optional):
1. Replace all odd numbers in the array with -1: `arr = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])`.
2. Create and reshape a 1D array into a 2D array with 2 rows.
3. Create two 2D arrays `a` and `b`, and vertically stack them.
4. Generate a pattern without hard coding: Input: `a = np.array([1,2,3])`, Output: `array([1, 1, 1, 2, 2, 2, 3, 3, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3])`.
5. Find common elements between arrays `a` and `b`: `a = np.array([1,2,3,2,3,4,3,4,5,6])`, `b = np.array([7,2,10,2,7,4,9,4,9,8])`.
6. Find the indices of the first 5 maximum values in the array `a`: `np.random.seed(100)`, `a = np.random.uniform(1,50, 20)`.
7. Remove all NaN values from a one-dimensional array: `a=np.array([1,2,3,np.nan,5,6,7,np.nan])`.
8. Calculate the Euclidean distance between two arrays `a` and `b`: `a = np.array([1,2,3,4,5])`, `b = np.array([4,5,6,7,8])`.
9. Find the index of the 5th occurrence of the number 1 in the array `x`: `x = np.array([1, 2, 1, 1, 3, 4, 3, 1, 1, 2, 1, 1, 2])`.
10. Identify repeated entries (from the 2nd occurrence onwards) in the given array and mark them as True. The first occurrence should be False: `np.random.seed(100)`, `a = np.random.randint(0, 5, 10)`.
</details>

## Getting_to_know_Pandas
<details>
  <summary>Click to expand/collapse</summary>
Read the data from the table "Birth Rate in the Regions of Ukraine (1950—2019)" - https://uk.wikipedia.org/wiki/%D0%9D%D0%B0%D1%81%D0%B5%D0%BB%D0%B5%D0%BD%D0%BD%D1%8F_%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D0%B8

1. Display the first rows of the table using the `head` method.
2. Determine the number of rows and columns in the DataFrame (use the `shape` attribute).
3. Replace the "-" values in the table with NaN values.
4. Determine the types of all columns using `dataframe.dtypes`.
5. Replace non-numeric column types with numeric ones. Hint: these are columns where the "-" symbol was found.
6. Calculate the proportion of missing values in each column (use the `isnull` and `sum` methods).
7. Remove the data for the entire country, the last row of the table.
8. Replace missing values in columns with the mean of the respective columns (use the `fillna` method).
9. Get a list of regions where the birth rate in 2019 was higher than the national average.
10. In which region was the highest birth rate in 2014?
11. Build a bar chart of birth rates by region in 2019.
</details>

## File_Analysis
<details>
  <summary>Click to expand/collapse</summary>
Conduct an analysis of the file 2017_jun_final.csv. The file contains the results of a survey of developers in June 2017.

1. Read the file 2017_jun_final.csv using the read_csv method.
2. Read the obtained table using the head method.
3. Determine the size of the table using the shape method.
4. Determine the data types of all columns using the dataframe.dtypes.
5. Calculate the proportion of missing values in each column (use the isnull and sum methods).
6. Remove all columns with missing values except the "Programming Language" column.
7. Calculate again the proportion of missing values in each column and make sure that only the "Programming Language" column remains.
8. Remove all rows in the original table using the dropna method.
9. Determine the new size of the table using the shape method.
10. Create a new table python_data, which will only contain rows with specialists who indicated Python as their programming language.
11. Determine the size of the python_data table using the shape method.
12. Using the groupby method, perform grouping by the "Position" column.
13. Create a new DataFrame where for the grouped data by the "Position" column, perform data aggregation using the agg method and find the minimum and maximum values in the "Monthly Salary" column.
14. Create a function fill_avg_salary, which will return the average monthly salary. Use it for the apply method and create a new column "avg".
15. Create descriptive statistics using the describe method for the new column.
16. Save the obtained table to a CSV file.
</details>

