# Citi Bike Analytics
![Pop](popular.jpg)
**The popularity of a Starting or an Ending stations is indicated by the size of its marker. The larger the marker the more popular a station is. In these vizualizations popularity is defined by the total number of trip records the station had in 2018. The color of each marker show the median age of the riders at the starting and ending stations. An interesting observation is that the popular stations are located between Jersey City and the Hudson River. Also the median age of riders at the most popular starting and ending station is 36.**
# 
![Distance](distance.jpg)
**This distance was calcualted using the following formula : <br>
   `Distance, d = 3963.0 * arccos[(sin(lat1) * sin(lat2)) + cos(lat1) * cos(lat2) * cos(long2 – long1)]`  <br>
   (https://www.geeksforgeeks.org/program-distance-two-points-earth/#:~:text=For%20this%20divide%20the%20values,is%20the%20radius%20of%20Earth) <br>
   In terms of total distance traveled by riders in 2018, it appears that between June to August the most miles were traveled. When Looking at total distance traveled in 2018 by age group, it appears that riders who have traveled the most miles in 2018 are betweent the ages of 25 to 34. This insteresting since the median age of the popular stations was 36 which is not too far from the 25-34 age group. When looking at total distance traveled in 2018 by gender, it appears that riders who identified themselves as males traveled the most miles in total.**
# 
![Mileage](mileage.jpg)
**Looking at the bikes with high average mileage in 2018, the bikes that were used by both costumers and subscribers had the highest avgerages. However, when looking at that same data broken down by gender, it appears that riders who are classified as costumers mostly consist of people who did not identify their gender or people who identified as male. For the most part it appears that people who identify as female were classified as subscribers.**

## Potential Issues
Since citibike only includes trips that begins at publicly available stations i.e., excluding trips that originate at our depots for rebalancing or maintenance purposes, there are less starting stations than ending stations which leaves the data unbalanced and could skew the starting station popularity.


