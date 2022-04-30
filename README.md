# PyBer_Analysis
BootCamp Module 5

It's your second week as a data analyst at PyBer, a ride-sharing app company valued at $2.3 billion. You've just been assigned your first big project: analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.

Python v3.9.7 | matplotlib v3.5.1 | Pandas v# | Anaconda v#

## Deliverable 1: A ride-sharing summary DataFrame by city type

You will earn a perfect score for Deliverable 1 by completing all requirements below:

• The total number of rides for each city type is retrieved.

• The total number of drivers for each city type is retrieved.

• The sum of the fares for each city type is retrieved.

• The average fare per ride for each city type is calculated.

• The average fare per driver for each city type is calculated.

• A PyBer summary DataFrame is created.

• The PyBer summary DataFrame is formatted as shown in the example.

The code and output for the PyBer Summary DataFrame is below:

![image](analysis/PyBer_1.png "pyber_summary_df")

## Deliverable 2: A multiple-line chart of total fares for each city type

You will earn a perfect score for Deliverable 2 by completing all requirements below:

• A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time:

![image](analysis/PyBer_2.png "far_by_city_date_df")

• A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare":

![image](analysis/PyBer_3.png "fare_by_city_date_df.pivot")

• A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28:

![image](analysis/PyBer_4.png "fare_dates_df")

• A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week:

![imgae](analysis/PyBer_5.png "fare_dates_df.resample")

• An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. (10 pt)

![image](analysis/PyBer_6.png "Total Fare By City plot")

## Deliverable 3: A written report for the PyBer analysis

### Overview

### Results

** use chats/grpahs

### Summary
