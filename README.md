# PyBer_Analysis
## Challenge

###Description 
  After a meeting with V. Isualize, where we presenting various data on PyBer, we have received an additional assignment to create a summary DataFrame of the key statistics by city type as well as a visualization showing the total fares for each week for each type of city. 

###Results
![]
![] 

###Steps and Analysis
	After a meeting with V. Isualize, where we presenting various data on Pyber, we have received an additional assignment to create a summary DataFrame of the key statistics by city type as well as a visualization showing the total fares for each week for each type of city. For summary DataFrame, we created various series for each category using the groupby function and grouping by type. The only category that did not utilize this method was “Average Fare per Driver”, which used simple division of “Total Fares” by “Total Drivers”. After that, we used these series to compiled a new DataFrame called “final_summary_df”, which displays our first Technical Analysis Deliverable. For the second analysis we created a multiple line chart that shows the total fare per week by city. To do this we created a pivot table DataFrame with its index being the date and the columns being the fares in categories by city. After that we put the DataFrame in bins by weeks and lastly plotted the data using the ‘fivethirtyeight’ format. 
	In these analysis we can see that there is an inverse relationship between total drivers/rides and the average fare per ride/driver. These findings translate to the total fare by city type chart we created in the second analysis as Urban cities had the highest total fares every week. 
  
###Challenges/Difficulties
  While I did not run into any challenges or difficulties during this challenge there are some that could come about.  An issue that could occur during this is not having your index set to date time. This could be a potential problem because if the index of the DataFrame is not set to this then you cannot separate the data into bins by week for the multiple line chart. 

###Recommendations for CEO
  In order to fix the disparities between the city types it is important to increase the demand in suburban and rural cities, so that PyBer can received more revenue. To do this I suggest PyBer try to increase user engagement as well as decrease the prices in order to increase the frequency of people using the ride-sharing service in the rural and suburban areas. Additional analyses that could be used would be to find average rides per day per capita for each city then focus in on certain cities where there is not a lot of engagement, as well as doing a bar chart that compares income, number of rides, and average fare per ride for each city to see if prices are too expensive for a given city. In order to complete these analysis we would need to gather additional datasets like average income for a city as well as population size. 
