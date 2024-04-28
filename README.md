# TASKS

## intro_data_science
<details>
  <summary>Click to expand/collapse</summary>

  **PART 1**

1. Create a one-dimensional array (vector) with the first `10` natural numbers and print its values.
2. Create a two-dimensional array (matrix) of size `3x3`, fill it with zeros, and print its values.
3. Create a `5x5` array, fill it with random integers in the range from `1` to `10`, and print its values.
4. Create a `4x4` array, fill it with random floating-point numbers in the range from `0` to `1`, and print its values.
5. Create two one-dimensional arrays of size `5`, fill them with random integers in the range from `1` to `10`, and perform element-wise addition, subtraction, and multiplication.
6. Create two vectors of size `7`, fill them with arbitrary numbers, and find their dot product.
7. Create two matrices of size `2x2` and `2x3`, fill them with random integers in the range from `1` to `10`, and multiply them together.
8. Create a `3x3` matrix, fill it with random integers in the range from `1` to `10`, and find its inverse matrix.
9. Create a `4x4` matrix, fill it with random floating-point numbers in the range from `0` to `1`, and transpose it.
10. Create a `3x4` matrix and a vector of size `4`, fill them with random integers in the range from `1` to `10`, and multiply the matrix by the vector.
11. Create a `2x3` matrix and a vector of size `3`, fill them with random floating-point numbers in the range from `0` to `1`, and multiply the matrix by the vector.
12. Create two matrices of size `2x2`, fill them with random integers in the range from `1` to `10`, and perform element-wise multiplication.
13. Create two matrices of size `2x2`, fill them with random integers in the range from `1` to `10`, and find their product.
14. Create a `5x5` matrix, fill it with random integers in the range from `1` to `100`, and find the sum of its elements.
15. Create two matrices of size `4x4`, fill them with random integers in the range from `1` to `10`, and find their difference.
16. Create a `3x3` matrix, fill it with random floating-point numbers in the range from `0` to `1`, and find a column vector containing the sum of elements of each row of the matrix.
17. Create a `3x4` matrix with arbitrary integers and create a matrix with the squares of these numbers.
18. Create a vector of size `4`, fill it with random integers in the range from `1` to `50`, and find a vector with the square roots of these numbers.

**PART 2** (additional, optional)
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
Read the data from the table [Birth Rate in the Regions of Ukraine (1950—2019)](https://uk.wikipedia.org/wiki/%D0%9D%D0%B0%D1%81%D0%B5%D0%BB%D0%B5%D0%BD%D0%BD%D1%8F_%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D0%B8)

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
6. 1. Remove all columns with missing values except the "Programming Language" column.
   2. Calculate again the proportion of missing values in each column and make sure that only the "Programming Language" column remains.
7. Remove all rows in the original table using the dropna method.
8. Determine the new size of the table using the shape method.
9. Create a new table python_data, which will only contain rows with specialists who indicated Python as their programming language.
10. Determine the size of the python_data table using the shape method.
11. Using the groupby method, perform grouping by the "Position" column.
12. Create a new DataFrame where for the grouped data by the "Position" column, perform data aggregation using the agg method and find the minimum and maximum values in the "Monthly Salary" column.
13. Create a function fill_avg_salary, which will return the average monthly salary. Use it for the apply method and create a new column "avg".
14. Create descriptive statistics using the describe method for the new column.
15. Save the obtained table to a CSV file.
</details>

##  Analyze_the_dataset_from_Kaggle.com
<details>
  <summary>Click to expand/collapse</summary>
   Utilize data from the Top-50 bestselling books on Amazon for 11 years (from 2009 to 2019). The dataset is publicly available on Kaggle.com. Download the CSV file from the link and move it to the same directory as your working notebook for convenience. Then proceed to the tasks.

   For this part of the task, you will need to not only write the code but also answer accompanying questions. Wherever you see bold text "Answer:", you will need to insert the question into the file and provide the answer to it.
<hr/>

**PART 1: Initial data**
<br/>
**DESCRIPTION: Prepare table**

1. Read the csv file (use the read_csv function)
2. Output the first five lines (the head function is used)
3. Display the dimensions of the dataset (use the shape attribute)
- `Question`  How many books does the dataset store?

7 variables (columns) are available for each of the books. Let's take a closer look at them:
Name - the name of the book
Author - the author
User Rating - rating (on a 5-point scale)
Reviews - number of reviews
Price - price (in dollars as of 2020)
Year - the year when the book entered the Top-50 rating
Genre - a genre

To simplify further work, let's tweak the variable names a little. As you can see, here all the names start with a capital letter, and one even contains a space. This is highly undesirable and can be quite inconvenient. Let's change the case to lowercase, and replace the space with an underscore (snake_style). And now we will study a useful data frame attribute: columns (you can simply assign a list of new names to this attribute)

df.columns = ['name', 'author', 'user_rating', 'reviews', 'price', 'year', 'genre']

**PART 2: Initial data exploration**
<br/>
**DESCRIPTION: Check Missing Values and Unique Genres**

1. Check if all rows have enough data: output the number of missing values (na) in each of the columns (use the isna and sum functions).
- `Question`  Are there any missing values in any of the variables? (Yes/No)
2. Check what unique values are in the "genre" column (use the unique function). 
- `Question`  What are the unique genres?
3. Determine the maximum, minimum, mean, and median prices (use the max, min, mean, and median functions). 
- `Question`  What is the maximum price? 
- `Question`  What is the minimum price? 
- `Question`  What is the mean price? 
- `Question`  What is the median price?
4. Now, look at the distribution of prices: create a histogram (use kind='hist').
<hr/>

**PART 3: Data search and sorting**
<br/>
**DESCRIPTION: Analysis of Book Ratings, Reviews, and Prices**

- `Question`  What is the highest rating in the dataset?
- `Question`  How many books have such rating?
- `Question`  Which book has the most reviews?
- `Question`  Among the books that made it to the Top 50 in 2015, which one is the most expensive (you can use an intermediate dataframe)?
- `Question`  How many Fiction genre books made it to the Top 50 in 2010 (use &)?
- `Question`  How many books with a rating of 4.9 made it to the rating in 2010 and 2011 (use | or the isin function)?
  - Finally, let's sort all books that made it to the rating in 2015 and cost less than $8 in ascending order of price (use the sort_values function). 
- `Question`  What is the last book in the sorted list?
<hr/>

**PART 4: Data aggregation and table merging**
<br/>
**DESCRIPTION: Aggregate Book Prices by Genre and Author**

1. First, let's look at the maximum and minimum prices for each genre (use the groupby and agg functions, for counting minimum and maximum values, use max and min). Do not take all columns, select only those you need.
- `Question`  What is the maximum price for the Fiction genre? 
- `Question`  What is the minimum price for the Fiction genre? 
- `Question`  What is the maximum price for the Non Fiction genre? 
- `Question`  What is the minimum price for the Non Fiction genre?
2. `Question`  Now, create a new dataframe that will contain the number of books for each author (use the groupby and agg functions, for counting, use count). Do not take all columns, select only those you need. 
- `Question`  What is the dimension of the resulting table? 
- `Question`  Which author has the most books? 
- `Question`  How many books does this author have?
3. `Question`  Now create a second dataframe that will contain the average rating for each author (use the groupby and agg functions, for calculating the average value, use mean). Do not take all columns, select only those you need. 
- `Question`  Which author has the minimum average rating? 
- `Question`  What is the average rating for this author?
4. Merge the last two dataframes so that for each author, you can see the number of books and the average rating (use the concat function with the axis parameter). Save the result in a variable.
5. Sort the dataframe in ascending order of the number of books and the rating (use the sort_values function). 
- `Question`  Which author is first on the list?
<hr/>

**PART 5: Visualization**
<br/>
**DESCRIPTION: Visualize Book Data Trends**

1. For each of the previous tasks, add `3` - `5` plots of different types of functions of your choice. Style the plots so that each graph in each work is different and not similar to others. You can use both matplotlib and seaborn.
2. Don't forget to add the directive `%matplotlib inline` to the Jupyter file so that the plots are built inside the document.
<hr/>
</details>


## linear_regression
<details>
  <summary>Click to expand/collapse</summary>
Read the data from the table [Housing](https://drive.google.com/file/d/1-rAa4XT4_fI0dOBlMNuE6a7jB0wln_Qo/view)

This homework assignment will be entirely related to linear regression and its implementation. So let's break our homework into several parts:

1. write a linear regression hypothesis function in vector form;
2. create a function to calculate the loss function in vector form;
3. implement one step of gradient descent;
4. find the best parameters **w** for a dataset using the functions you wrote that predict the price of a house depending on the area, number of bathrooms, and number of bedrooms;
5. find the same parameters using an analytical solution;
6. use LinearRegression from the scikit-learn library to check the predicted values and compare the results.
</details>


## Classification_and_evaluation_of_model_performance
<details>
  <summary>Click to expand/collapse</summary>

This time you need to complete the tasks from [this](https://colab.research.google.com/drive/1XpRovHlJJ16FZojZd8-9ci1pyiUiYogx?usp=sharing#scrollTo=B6rE566oF0cv) notebook. To solve the proposed tasks, you also need to download a dataset with [bike rental data](https://drive.google.com/file/d/1-4wgz9AFXrD3tZfqHJLMhCmy4BUzAX96/view).
</details>