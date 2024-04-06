# Homework Assignment - Working with data - Pandas 


<center>
  
![Alt Text](https://raw.githubusercontent.com/julotec/pandas_examples/assets/135429630/6bb0f9fb-26b6-4a7a-820a-7c309de18f57)

</center>



## Part One: Analyzing birth rate of Ukrainian inhabitants in 1950-2019
_______________________________________________________________________
The data analysis includes displaying the initial rows of the dataset, 
determining the number of rows and columns, replacing missing values, 
defining column data types, converting non-numeric columns to numeric, 
calculating the proportion of missing data, removing data for the entire
country, replacing missing values with column averages, identifying
regions with birth rates higher than the Ukrainian average,
finding the region with the highest birth rate, and creating a bar
chart showing birth rates by region.

### Step 1: Loading the CSV File

To load the CSV file, we will use the Pandas library in Python:



## Part Two : Analysis of a survey conducted among developers in June 2017
__________________________________________________________________________


This task involves reading a CSV file named "2017_jun_final.csv" using Pandas, 
performing data cleaning operations such as handling missing values and removing
unnecessary columns, and then conducting data analysis and aggregation. Finally, 
the processed data will be saved to a new CSV file.
The completed homework should be submitted as a Jupyter notebook file named "Hw2_2.ipynb".
### Step 1: Loading the CSV File

To load the CSV file, we will use the Pandas library in Python:

```
import pandas as pd

Load the data
data = pd.read_csv("2017_jun_final.csv")

```

## Part Three : Analysis of a survey conducted among developers in June 2017
____________________________________________________________________________

In this homework task, we delve deeper into the Pandas library, exploring more advanced functions. 
We utilize a dataset containing information about the top 50 bestselling books on Amazon over 11 
years (from 2009 to 2019). The tasks involve data preprocessing, exploratory data analysis, and aggregation.

We start by reading the CSV file, displaying the first few rows, and examining the dataset's dimensions. 
We then perform data cleaning tasks such as handling missing values and renaming columns. Exploratory 
analysis includes examining unique values in the "Genre" column and visualizing the distribution of prices.

Further analysis involves identifying the highest rating, the book with the most reviews, and the most 
expensive book in 2015. We also explore the number of books in the Fiction genre in 2010, identify books 
with a rating of 4.9 in 2010 and 2011, and sort books from 2015 by price.

Lastly, we aggregate data to find the maximum and minimum prices for each genre, count the number of books 
for each author, calculate the average rating for each author, and combine these into a single dataframe. 
The final step is sorting the dataframes by the number of books and the average rating.

The completed homework should be submitted as a Jupyter notebook file named "Hw2_3.ipynb".
