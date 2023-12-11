# Homework function wiki

This file contains a brief summary of all the functions used in the homework notebooks, as well as a link to the relevant documentation.

## Matplotlib Functions:

- `matplotlib.pyplot.bar`: This function is used to create a bar plot in Matplotlib. It takes in parameters like the x and y values, and can be customised with labels, colors, and other options. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.bar.html)

- `matplotlib.pyplot.boxplot`: This function is used to create a box plot in Matplotlib. It takes in a list of values and can be customised with labels, colors, and other options. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html)

- `matplotlib.pyplot.hist`: This function is used to create a histogram in Matplotlib. It takes in a list of values and can be customised with bins, labels, colors, and other options. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.hist.html)

- `matplotlib.pyplot.show`: This function is used to display the plot created using Matplotlib. It is typically called at the end of the plotting code. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.show.html)

- `matplotlib.pyplot.xticks`: This function is used to customise the x-axis tick labels in Matplotlib. It takes in parameters like the tick positions and labels. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.xticks.html)

- `matplotlib.pyplot.xlabel`: This function is used to set the label for the x-axis in Matplotlib. It takes in a string parameter representing the label text. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.xlabel.html)

- `matplotlib.pyplot.ylabel`: This function is used to set the label for the y-axis in Matplotlib. It takes in a string parameter representing the label text. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.ylabel.html)

- `matplotlib.pyplot.title`: This function is used to set the title of the plot in Matplotlib. It takes in a string parameter representing the title text. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.title.html)

- `matplotlib.pyplot.subplots_adjust`: This function is used to adjust the spacing between subplots in Matplotlib. It takes in parameters like the left, right, top, and bottom spacing values. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.subplots_adjust.html)

- `matplotlib.pyplot.suptitle`: This function is used to set the super title of the figure in Matplotlib. It takes in a string parameter representing the super title text. [Link to documentation](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.suptitle.html)


## Numpy Functions:

- `numpy.arange`: This function is used to create an array of evenly spaced values within a specified range. It takes in parameters like the start, stop, and step values. [Link to documentation](https://docs.scipy.org/doc/numpy/reference/generated/numpy.arange.html)

- `numpy.corrcoef`: This function is used to compute the correlation coefficient between two arrays. It takes in two arrays as parameters and returns the correlation matrix. [Link to documentation](https://docs.scipy.org/doc/numpy/reference/generated/numpy.corrcoef.html)


## Pandas Functions:

- `pandas.DataFrame.apply`: This function is used to apply a function to each row or column of a DataFrame. It takes in a function as a parameter and returns a new DataFrame with the applied function. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.apply.html)

- `pandas.DataFrame.boxplot`: This function is used to create a box plot for each column of a DataFrame. It takes in parameters like the column(s) to plot, labels, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.boxplot.html)

- `pandas.DataFrame.describe`: This function is used to generate descriptive statistics of a DataFrame. It provides information like count, mean, standard deviation, minimum, maximum, and quartiles. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.describe.html)

- `pandas.DataFrame.drop`: This function is used to drop specified labels from rows or columns of a DataFrame. It takes in parameters like the labels to drop and the axis (rows or columns). [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop.html)

- `pandas.DataFrame.dtypes`: This function is used to get the data types of each column in a DataFrame. It returns a Series with the column names as the index and the data types as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html)

- `pandas.DataFrame.groupby`: This function is used to group a DataFrame by one or more columns. It returns a GroupBy object that can be used for further analysis or aggregation. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html)

- `pandas.DataFrame.head`: This function is used to get the first n rows of a DataFrame. It takes in an optional parameter to specify the number of rows to return. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html)

- `pandas.DataFrame.hist`: This function is used to create a histogram for each column of a DataFrame. It takes in parameters like the column(s) to plot, bins, labels, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.hist.html)

- `pandas.DataFrame.isna`: This function is used to check for missing values in a DataFrame. It returns a DataFrame of the same shape as the input DataFrame, with True values where missing values are present. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isna.html)

- `pandas.DataFrame.loc`: This function is used to access a group of rows and columns by label(s) or a boolean array. It takes in parameters like the row(s) and column(s) to select. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.loc.html)

- `pandas.DataFrame.mean`: This function is used to calculate the mean of each column in a DataFrame. It returns a Series with the column names as the index and the mean values as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.mean.html)

- `pandas.DataFrame.min`: This function is used to calculate the minimum value of each column in a DataFrame. It returns a Series with the column names as the index and the minimum values as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.min.html)

- `pandas.DataFrame.max`: This function is used to calculate the maximum value of each column in a DataFrame. It returns a Series with the column names as the index and the maximum values as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.max.html)

- `pandas.DataFrame.plot.bar`: This function is used to create a bar plot for each column of a DataFrame. It takes in parameters like the column(s) to plot, labels, colors, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.bar.html)

- `pandas.DataFrame.plot.box`: This function is used to create a box plot for each column of a DataFrame. It takes in parameters like the column(s) to plot, labels, colors, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.box.html)

- `pandas.DataFrame.plot.hist`: This function is used to create a histogram for each column of a DataFrame. It takes in parameters like the column(s) to plot, bins, labels, colors, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.hist.html)

- `pandas.DataFrame.plot`: This function is used to create various types of plots (line, bar, scatter, etc.) for each column of a DataFrame. It takes in parameters like the column(s) to plot, labels, colors, and other options. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.html)

- `pandas.DataFrame.replace`: This function is used to replace specified values in a DataFrame. It takes in parameters like the values to replace and the new values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.replace.html)

- `pandas.DataFrame.reset_index`: This function is used to reset the index of a DataFrame. It returns a new DataFrame with the index reset to the default integer index. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.reset_index.html)

- `pandas.DataFrame.set_index`: This function is used to set the index of a DataFrame. It takes in parameters like the column(s) to use as the index and returns a new DataFrame with the specified index. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.set_index.html)

- `pandas.DataFrame.std`: This function is used to calculate the standard deviation of each column in a DataFrame. It returns a Series with the column names as the index and the standard deviation values as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.std.html)

- `pandas.DataFrame.value_counts`: This function is used to count the occurrences of unique values in a DataFrame. It returns a Series with the unique values as the index and the counts as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.value_counts.html)

- `pandas.Series.astype`: This function is used to change the data type of a Series. It takes in a data type as a parameter and returns a new Series with the specified data type. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.astype.html)

- `pandas.Series.apply`: This function is used to apply a function to each element of a Series. It takes in a function as a parameter and returns a new Series with the applied function. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.apply.html)

- `pandas.Series.value_counts`: This function is used to count the occurrences of unique values in a Series. It returns a Series with the unique values as the index and the counts as the values. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.value_counts.html)

- `pandas.Series.unique`: This function is used to get the unique values of a Series. It returns an array of the unique values in the Series. [Link to documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.unique.html)
