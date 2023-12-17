# Python for Data Science - Week 2 Data Handling : Initial reading

This file will explore a handful of topics that will be introduced in this week's homework. Please take some time to look over the content of this file as it will be a huge help when working through the notebooks. There is also a wiki file that contains a brief description of all the functions used in the homework notebooks to help you further understand. Good luck!

## Lambda functions in Python

Lambda functions, also known as anonymous functions, are small, single-line functions that do not require a `def` statement. They are commonly used when a function is needed for a short period of time and does not need to be defined separately. Lambda functions are defined using the `lambda` keyword, followed by the function parameters and a single expression.

## String and array slicing in Python

String and array slicing is a powerful feature in Python that allows you to extract a portion of a string or an array. Slicing is done using square brackets [] and a range of indices.

For strings, slicing allows you to extract a substring by specifying the start and end indices. The start index is inclusive, while the end index is exclusive. For example, `my_string[2:5]` will return the characters from index 2 to index 4 (not including index 5).

For arrays, slicing works in a similar way. You can extract a portion of an array by specifying the start and end indices. The start index is inclusive, while the end index is exclusive. For example, `my_array[1:4]` will return the elements from index 1 to index 3 (not including index 4).

Slicing can also accept a step value, allowing you to skip elements. For example, `my_string[::2]` will return every second character in the string.

## F-strings when printing variables

F-strings, short for formatted string literals, provide a concise and convenient way to embed expressions inside string literals. They are prefixed with the letter 'f' and enclosed in curly braces {}. F-strings allow you to directly insert variables and expressions into strings without the need for concatenation or formatting functions.

## Pandas DataFrame

A pandas DataFrame is a two-dimensional, labeled data structure that is widely used for data manipulation and analysis in Python. It consists of rows and columns, similar to a table or spreadsheet. DataFrames provide a powerful and flexible way to store, manipulate, and analyse structured data.

## Pandas Series vs DataFrame

In Pandas, a Series is a one-dimensional labeled array that can hold any data type. It is similar to a column in a spreadsheet or a single column of data in a table. A Series has both a sequence of values and a sequence of labels, called the index. The index allows for easy and efficient access to the data.

This is different to a DataFrame, which is a two-dimensional labeled data structure with columns of potentially different data types. It can be thought of as a table or a spreadsheet, where each column represents a variable and each row represents an observation. A DataFrame is more versatile and can handle complex data manipulations and analysis.

In short, a Series is a single column of data with an index, while a DataFrame is a collection of Series arranged in a tabular format. Understanding the difference between a Series and a DataFrame is crucial for effectively working with pandas and performing data analysis tasks.

## Pandas .apply() function in conjunction with lambda functions

The `apply` function in pandas is used to apply a function along an axis of a DataFrame or Series. When combined with lambda functions, it allows you to apply custom operations to each row or column of a DataFrame. This can be useful for performing calculations, transformations, or filtering based on specific conditions.

## Correlation

Correlation is a statistical measure that quantifies the relationship between two variables. It indicates the strength and direction of the linear relationship between the variables. Correlation coefficients range from -1 to 1, where -1 represents a perfect negative correlation, 1 represents a perfect positive correlation, and 0 represents no correlation.

## Boxplots, histograms & bar charts

Boxplots, histograms, and bar charts are commonly used visualisations in data analysis and data visualisation. 

- Boxplots provide a visual summary of the distribution of a dataset, displaying the minimum, first quartile, median, third quartile, and maximum values. They are useful for identifying outliers and comparing distributions.
- Histograms display the distribution of a continuous variable by dividing it into bins and counting the number of observations in each bin. They provide insights into the shape, central tendency, and spread of the data.
- Bar charts are used to compare categorical data by displaying the frequency or proportion of each category as bars. They are effective for visualising categorical variables and identifying patterns or trends.

## Supporting material

* [Intro to Pandas using the Iris dataset](https://www.geeksforgeeks.org/python-basics-of-pandas-using-iris-dataset/)
* [Intro to Matplotlib](https://www.geeksforgeeks.org/python-introduction-matplotlib/)
* [Plotting the Iris dataset with Matplotlib](https://www.geeksforgeeks.org/plotting-graph-for-iris-dataset-using-seaborn-and-matplotlib/)
* [Intro to lambda functions](https://www.w3schools.com/python/python_lambda.asp)
* [Commonly used Pandas functions](https://www.sharpsightlabs.com/blog/19-pandas-functions-you-need-to-memorize/)

Note: The following links essentially cover what is asked of you in this week's homework... only use if you're very stuck!

* [Data analysis on the Iris dataset](https://www.geeksforgeeks.org/exploratory-data-analysis-on-iris-dataset/)
* [Even more data analysis on the Iris dataset](https://towardsdatascience.com/eda-of-the-iris-dataset-190f6dfd946d)
