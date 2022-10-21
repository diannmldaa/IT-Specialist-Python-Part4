# IT-Specialist-Python-Part4

**1. Pandas**

Pandas is a library in Python that provides easy-to-use data structures and data analysis. Pandas is commonly used to create tables, change data dimensions, check data, and so on. The basic data structure in Pandas is called DataFrame, which makes it easy for us to read a file with many types of formats such as .txt, .csv, and .tsv files. This feature will make it a table and can also process data using operations such as join, distinct, group by, aggregation, and other techniques found in SQL.

import pandas = import pandas as pd

- Data Series

   Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.). The axis labels are collectively   called index.
 
- loc and iloc
   * loc is label-based, which means that you have to specify rows and columns based on their row and column labels
   * iloc is integer position-based, so you have to specify rows and columns by their integer position values (0-based integer position)

- Data Frame

   A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.

   * Pandas import csv file

     The pandas function read_csv() reads in values, where the delimiter is a comma character. You can export a file into a csv file in any modern office suite including Google Sheets

   * head() function
  
     This function returns the first n rows for the object based on position. It is useful for quickly testing if your object has the right type of data in it.
   
   * info() function
   
     This function can see the column name, the number of Non-Null values and the type of data in each column in the 'Titanic' data.
   
   * notnull().sum() function
   
     This function to see the amount of data filled in from each column.
     
   * isnull().sum() function
     
     This function to see the empty value of each Titanic data column.
    
   * sum() function

     This function counts up all the data in each column.
     
   * tail() function
   
     This function to see the entire contents of the Titanic data starts from the bottom to the top.
     
   * shape() function
   
     Shape function to see the count of rows and columns in the data (row, column)
     
   * column() function
   
     Column function to see the column names in the data.
     
   * index() function
   
     Index function to see the count of rows in the data.
     
   * describe() function
   
     Describe the function to see statistics from each column in the data. Statistics include count, mean, std, min, and max.
     
   * mean() and median() function
   
     Mean and median functions to see the average and central value of data.
     
   * unique() function
   
     Unique function to see the unique value (different value) of data.
     
   * value_counts() function

     This function to see the amount of each unique value in the data.
  
**2. Matplotlib**
  
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible. The advanteges using matplotlib are customize visual style and layout, export to many file formats and embed in JupyterLab and Graphical User Interfaces.

import library matplotlib = import matplotlib.pyplot as plt

- line chart

   To make line chart using matplotlib, first import Matplotlib.pyplot library for plotting functions. Also, import the Numpy library as per requirement. Then define data values x and y. 

- bar chart

   A bar chart or bar graph is a chart or graph that presents categorical data with rectangular bars with heights or lengths proportional to the values that they represent. The bars can be plotted vertically or horizontally. With Pyplot, you can use the bar() function to draw bar graphs

- stack bar chart

   Stacked bar plots represent different groups on the highest of 1 another. The peak of the bar depends on the resulting height of the mixture of the results of the groups. It goes from rock bottom to the worth rather than going from zero to value
   
   * title
      
      we can also customize the title of the cart by using the syntax = plt.title('title name')
    
   * label
   
      cutomize label using syntax = plt.xlabel('xAxis name') ; plt.ylabel('yAxis name')
      
   * legend
   
      cutomize label using syntax = plt.legend(['x1Axis name', x2Axisname)
      
   * figsize
   
      customize size figure uring syntax = plt.figure(figsize=(width,length))
  
**3. Seaborn**
  
Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

import library seabron = import seaborn as sns

- line chart

   Seaborn Line Plots depict the relationship between continuous as well as categorical values in a continuous data point format.

- bar chart

   A barplot is basically used to aggregate the categorical data according to some methods and by default it’s the mean. It can also be understood as a visualization of the group by action. To use this plot we choose a categorical column for the x-axis and a numerical column for the y-axis, and we see that it creates a plot taking a mean per categorical column.
   
- stack bar chart

   A stacked Bar plot is a kind of bar graph in which each bar is visually divided into sub bars to represent multiple column data at once. 
   
   * hue parameter
   
     Grouping variable that will produce lines with different colors. Can be either categorical or numeric, although color mapping will behave differently in latter case.
    
   * set style
   
      Customize seaborn chart sucing set.style('theme')
    

   
