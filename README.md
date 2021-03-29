# PyBer_Analysis
The ride-sharing company PyBer wanted to analyze and visualize multiple different trends to make conclusions about trends within the application. As part of the analysis, PyBer wanted to see line graphs, bar charts, box-and-whisker plots, scatter plots, pie charts, and Pandas DataFrames in order to visualize all of the ride sharing data that was provided.

## Resources
- Software: Python 3.7.6, JuptyerNotebook 6.1.4

## Overview of the Ride Share Analysis
The purpose of the challenge analysis was to use Pandas and MatPlotLib to create multiple-line graphs that show the total weekly fares for each city type. The purpose of the analysis and the challenge was to gain an understanding of how ride sharing fares differ across the different city types. The company wanted to investigate ride-sharing patterns in the three different city types, urban, suburban, and rural.

## Results
### Deliverable 1: A ride sharing DataFrame that summarizes ride data by city type.
![Deliverable_1](https://github.com/jackogross123/PyBer_Analysis/blob/main/Resources/PyBer_summary_DF.png)

By creating multiple different dataframes by using the groupby(), count(), and sum() function, I was able to create this DataFrame to depict how ride sharing data differed across the three different city types. One of the biggest takeaways from the DataFrame is that drivers within the rural areas make the most money followed by suburban and then urban drivers. Moreoever, the average price for drive is the most expensive in rural places followed by sububran and then rural. There are the most amount of drivers in urban places and the least in rural communities.

### Deliverable 2: A multiple-line chart of total fares for each city type.
![Deliverable_2](https://github.com/jackogross123/PyBer_Analysis/blob/main/Resources/Total_fare_by_city_type_graph.png)

By creating multiple different data series and using the groupby(), loc(), resample(), and sum() formulas I was able to create this graph to depict by using MatPlotLib to show the relationship between time and daily fares. There are three different lines to represent how the fare rates differ across city types. Urban cities bring in the most revenue, followed by suburban, and then rural. The chart that was created answers the question of which type of drivers bring in the most revenue, however, it would be helpful to see how this compares to daily wages for the drivers.

## Summary
From deliverable 1, I imagine that the reason as to why the rides are most expenive in rural communities and that rural drivers make the most money is because they are most likely driving the longest distances. On average, rural drivers are making the most money per ride and rural riders are paying the most money. That being said, rural communities have the highest total driver to driver ratio which may lead one to believe that it would be more profitable to drive in rural communities as opposed to cities where the number of total drivers outnumbers the amount of total rides by over 800. As it can be seen in the graph, the most amount of money is made by urban drivers because they're giving the most amount of rides per day. However, this does not answer the question of what type of drivers are the most profitable. I think that it may be valuable to explore more driving in rural areas. It has the most opportunity for growth and drivers have the opportunity to make the most money. 

### Reccomendations 
I think that one study that should be purused is measuring the length of the rides and the fare prices. It would be helpful to explore how different length rides (time and physical distance) differ within the three different city types. It would also be interesting to see how this relates to daily profits for the drivers in each of the different city types. It would also be valuable to see how on a day to day basis what kinds of drivers make the most money on average. 
