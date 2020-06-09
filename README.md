# Green-Taxi-Data-Analysis-

## Performance of Tools ##

The goal of this assignment is to study the relative performance of a set of tools: pandas, dask, vaex, HDF5 and PySpark. We will follow the article "How to analyze 100 GB of data on your laptop with Python" which is at https://towardsdatascience.com/how-to-analyse-100s-of-gbs-of- data-on-your-laptop-with-python-f83363dda94. You should read that article before starting this assignment.
In that article Jovan Veljanoski analysis 100 GB of Yellow Taxi data from New York City. Since some students may not have 100 GB of free disk space we will use the data from the Green taxi company, which is only 10GB of data. You can download the data from the assignment page for the class. Note that the data dictionary for the Green Taxi data has slightly different labels for two fields. The article has Jupiter notebook of the analysis done in the article so you might want to look at that.
You are going to measure the time it take to perform the following tasks using pandas, dask, vaex and PySpark.
• Plot the number of unique trips with certain number of passengers in the entire green taxi data. (Green taxis can not operate in parts of NYC.)
• Filteroutthetripslongerthan100milesandtripsthatclaimmorethan10people.
• On the filtered data produce a heat map by pick up location color coded by average fare amount,
• Compute the arc distance for the filtered data and plot the distribution number of trips of trip distance and arc distance.
The article contains the code to perform these operations. The goal of this assignment is to compare using pandas, dask, vaex and PySpark to perform the above task. Runtime perfor- mance of each to perform the task is one metric to report. But also discuss any issues the you had with using any of the 4 systems.
You also need to convert the data from a collection of CSV field into a single HDF5 file. You are to use that file as input.
