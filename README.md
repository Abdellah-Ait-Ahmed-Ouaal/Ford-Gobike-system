# Ford GoBike Data Exploration

## by Abdellah Ait Ahmed Ouaal


## Dataset

The dataset consists of 183413 records concerning individual trips made in a bike-sharing system (GoBike) covering the greater San Francisco Bay area, with 16 columns including: the duration in seconds, the starting and ending time, gender(male, female, other) and type(subscriber or customer) of the user for each trip in the year 2019.
The dataset can be foun in [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

## Summary of Findings

In the exploration, i found that the numerical variable duration of the trip has a log-normal distribution with a mean of 704 seconds, with trips of long duration occur on weekends more than other days, also men take shorter trips comparing to other genders. Additionally the day and hour with most number of trips are respectively thursday followed by tuesday and 17:00 followed by 18:00, and subscribers take about 90% of the proportion of users while men take about 75% of the same proportion.

Finally trips of customer users have three properties: first they are longer in duration than subscriber trips across all genders, second the number of trips each day excluding thursday is between 2000 and 2600 trips which means this distribution has a low dispersion comparing to subscribers distribution, third the second day when most trips are taken is friday instead of tuesday. 

## Key Insights for Presentation

For the presentation, I focus only on just the influence of the categorical variables gender and user type over the duration of the trip. I start by introducing the main numerical variable duration in seconds, then plot its distribution using histograms in the transformed log-scale.

Afterwards, I introduce each of the two categorical variables one by one. To start, I use two pie charts to show the total number of trips frequency per user type and gender because pie charts are the clearest way to show those proportions, next I use box plots of duration across gender and duration across user type since we have qualitative vs quantitative variables and the best suit is box plot. Finally I use violin plot of duration across both gender and user type to get the best insights from those three variables.