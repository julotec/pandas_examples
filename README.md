# Homework Assignment

## Part One: Analyzing birth rate of Ukrainian inhabitants in 1950-2019
_______________________________________________________________________
The data analysis includes displaying the initial rows of the dataset, determining the number of rows and columns, replacing missing values, defining column data types, converting non-numeric columns to numeric, 
calculating the proportion of missing data, removing data for the entire country, replacing missing values with column averages, identifying regions with birth rates higher than the Ukrainian average,
finding the region with the highest birth rate, and creating a bar chart showing birth rates by region.

### Step 1: Loading the CSV File

To load the CSV file, we will use the Pandas library in Python:



## Part Two One: Analyzing birth rate of Ukrainian inhabitants in 1950-2019
_______________________________________________________________________

In this homework assignment, we will be analyzing a CSV file containing the results of a survey conducted among developers in June 2017.

### Step 1: Loading the CSV File

To load the CSV file, we will use the Pandas library in Python:


```python
import pandas as pd

Load the data
data = pd.read_csv("2017_jun_final.csv")
