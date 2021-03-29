# PyBer_Analysis
The ride-sharing company PyBer wanted to analyze and visualize multiple different trends to make conclusions about trends within the application. As part of the analysis, PyBer wanted to see line graphs, bar charts, box-and-whisker plots, scatter plots, pie charts, and Pandas DataFrames in order to visualize all of the ride sharing data that was provided.

## Resources
- Software: Python 3.7.6, JuptyerNotebook 6.1.4

## Overview of the Ride Share Analysis
The purpose of the challenge analysis was to use Pandas and MatPlotLib to create multiple-line graphs that show the total weekly fares for each city type. The purpose of the analysis and the challenge was to gain an understanding of how ride sharing fares differ across the different city types. The company wanted to investigate ride-sharing patterns in the three different city types, urban, suburban, and rural.

## Results
### Deliverable 1: A ride sharing DataFrame that summarizes ride data by city type.
![Deliverable_1](https://github.com/jackogross123/PyBer_Analysis/blob/main/Resources/PyBer_summary_DF.png)

By creating multiple different dataframes by using the groupby(), count(), and sum() function, I was able to create this DataFrame to depict how ride sharing data differed across the three different city types. 

### Deliverable 2: A multiple-line chart of total fares for each city type.
![Deliverable_2](https://github.com/jackogross123/PyBer_Analysis/blob/main/Resources/Total_fare_by_city_type_graph.png)

By creating multiple different data series and using the groupby(), loc(), resample(), and sum() formulas I was able to create this graph to depict by using MatPlotLib to show the relationship between time and daily fares. There are three different lines to represent 
## Summary

### Reccomendations 
I think that one study that should be purused is measuring the length of the rides and the fare prices. It would be helpful to explore how different length rides (time and physical distance) differ within the three different city types.
