## About data
This wildfire dataset contains data on fire activities in Australia starting from 2005. Additional information can be found here.
The dataset includes the following variables:

Region: the 7 regions
Date: in UTC and provide the data for 24 hours ahead
Estimated_fire_area: daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for a each region in km2
Mean_estimated_fire_brightness: daily mean (by flagged fire pixels(=count)) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin
Mean_estimated_fire_radiative_power: daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts
Mean_confidence: daily mean of confidence for presumed vegetation fires with a confidence level > 75%
Std_confidence: standard deviation of estimated fire radiative power in megawatts
Var_confidence: Variance of estimated fire radiative power in megawatts
Count: daily numbers of pixels for presumed vegetation fires with a confidence level of larger than 75% for a given region
Replaced: Indicates with an Y whether the data has been replaced with standard quality data when they are available (usually with a 2-3 month lag). Replaced data has a slightly higher quality in terms of locations
Part 1 : Analyzing the wildfire activities in Australia
Objective:
The objective of this part of the Practice Assignment is to analyze and visualize the wildfire activities in Australia using the provided dataset. You will explore patterns and trends, and create visualizations to gain insights into the behavior of wildfires in different regions of Australia.

## data Visualization
 - average estimated fire area over time using pandas to plot the line chart.
 - Plot the estimated fire area over month between (2010:2013) as this is most years in fires
 - develop a barplot to find the insights on the distribution of mean estimated fire brightness across the regions
 - Develop a pie chart and find the portion of count of pixels for presumed vegetation fires vary across regions
 - Customize the previous pie plot for a better visual representation
 - develop a histogram of the mean estimated fire brightness
 - distribution of estimated fire brightness across regions by hue
 - 
scatter plot to find the correlation between mean estimated fire radiative power and mean confidence level
