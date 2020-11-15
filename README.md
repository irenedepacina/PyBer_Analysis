# PyBer_Analysis
Matplotlib

creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods

Python graphing library Matplotlib, which is a favorite tool among data scientists and data analysts because of its robust visualization features

Import your data into a Pandas DataFrame.
Merge your DataFrames.
Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
Determine the mean, median, and mode for the following:
The total number of rides for each city type.
The average fares for each city type.
The total number of drivers for each city type.
Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
The number of rides for each city type.
The fares for each city type.
The number of drivers for each city type.
Create a pie chart that visualizes each of the following data for each city type:
The percent of total fares.
The percent of total rides.
The percent of total drivers.

For the bubble chart, we will need to plot the following:

The average fare for each type of city on the y-axis
The total number of rides for each type city on the x-axis
Make the size of each marker, or bubble, correlate to the average number of drivers for each type of city

Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.