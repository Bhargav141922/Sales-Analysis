# Sales-Analysis
We will use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## We start by cleaning our data. Tasks during this section include:

1)Drop NaN values from DataFrame
2)Removing rows based on a condition
3)Change the type of columns (to_numeric, to_datetime, astype)
4)Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 4 high level business questions related to our data:

1)What was the best month for sales? How much was earned that month?
2)What city sold the most product?
3)What products are most often sold together?
4)What product sold the most? Why do you think it sold the most?
To answer these questions we walk through many different pandas & matplotlib methods. They include:

a)Concatenating multiple csvs together to create a new DataFrame (pd.concat)
b)Adding columns
c)Parsing cells as strings to make new columns (.str)
d)Using the .apply() and .transform() method
e)Using groupby to perform aggregate analysis
f)Plotting bar charts
