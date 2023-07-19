# Matplotlib Challenge

## Pymaceuticals Jupyter Notebook

### Overview
-----------------------------------------------------------------------------------
This Python program is designed to provide analysis on a study of the effectiveness of various drug regimens at reducing the tumor volume in mice. The python program involves using pandas to pull in CSV files, merge two dataframes, create dataframes based on filtered data, and matplotlib for data visualization in the form of bar graphs, box plots, pie charts, and line plots. This program also allows the user to conduct statistical analysis on the data to draw meaningful conclusions. The data used in this program should be properly formatted using pandas to eliminate duplicate mice within the data set.

### Main Function
-----------------------------------------------------------------------------------
-Data Loading: Loads the data from the CSV file into a pandas DataFrame. Merges the two dataframes created from the CSV files into one DataFrame.

-Data Cleaning: Performs any necessary data cleaning steps, such as removing duplicate entries. 

-Data Visualization: Uses matplotlib to create various plots and visualizations to analyze the data. Some of the visualizations include:

* Line plots to show tumor volume changes over time for the Capomulin drug regimen.
* Bar plots to compare the effectiveness of different drug regimens.
* Box plots to visualize the variance and outliers of tumor volume data for Capomulin, Ramicane, Infubinol, Ceftamin.
* Scatter plots to identify correlations between average tumor volume and weight of the mice.

-Statistical Analysis: Conducts statistical analysis on the data to derive insights.
* Calculating the mean, median, variance, standard deviation, and SEM value of the tumor volume for each drug regimen. 

### Example Output
-----------------------------------------------------------------------------------
![Capture](https://github.com/nCervantez/MatplotlibChallenge/assets/134685991/43c93119-216c-47d1-8f54-5972f385d1ce)
