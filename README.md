# Project: Investigation on the trip duration and distance that FordGobike users travel

## Introduction
The data set was obtained from [FordGobike](https://www.fordgobike.com/system-data). This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in 2017. There are 519,700 observations in the data set with originally 15 features. Seven more features generated from original features were added to the dataset.

## Objective
This project aimed to use data visualization to explore and explain the data, and eventually communicate the insights from the data analysis.

## Methodology
### Techonologies used
- Jupyter notebook (Python)
- Python libraries: Numpy, Pandas, Matplotlib, Seaborn
### Methodologies
- Data wrangling
- Exploratory visualization
- Explanatory visualization

## Summary of Findings
In the exploration, I expected to see strong correlation between the trip duration/distance and time features (time range, day of week). I could see when is the time users spend the longest trip duration and distance. Additionally, velocity of the trip was calculated from the trip duration and distance. The trend of Gobike use by both male and female users are more or less similar. Surprisingly, age of users do not correlate with the trip duration, distance and velocity.

Other than the investigation on the trip, I explored correlations of the age of users and some features. The age of the male members are higher than the age of the female members. The age tends to have negative correlation with time range for both male and female. Younger male and female members tend to ride GoBike more during Sat-Sun.


## Key Insights for Presentation
For the presentation, I focus on just the main interest features, which are the trip duration, distance. I start by showing the distribution of trip duration and distance. Then, I show the count plots of time features and found that the data was collected from June 2017.

To see the relationship of the variables of interest, I started with the boxplot to show the relationship between numerical and categorical variables. I focus on the trend of gender of users that use GoBike in diferrent time periods. I also show that the age does not correlate with the trip duration, distance and velocity by scatter plot. Mainly, barplot is used for multivariate exploration and each gender is separated by different colors. The relationship between time features is also shown by different color palette to distinct the different variables. 

## References
[1] https://s3.amazonaws.com/fordgobike-data/index.html <br>
[2] https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude/43211266#43211266 <br>
[3] https://en.wikipedia.org/wiki/Ford_GoBike