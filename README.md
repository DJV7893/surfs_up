# surfs_up

---
## Overview
---
### Purpose:

  Our initial analysis for a potential investor, W.Avy, in our surf shop consisted of inspecting and extracting relevant weather data from the island of Oahu, Hawaii stored in a SQLite database. From the database we queried precipitation levels over the span of a year starting from August 23,2016 to August 23, 2017. To display trends in precipitation levels we then created a plot of precipitation scores in chronological order. Rather than simply showing whether it rained on a given day, we showed how much it rained and if it was raining on the previous or subsequent days as well. In addition to the plot, we provided solid statistical analysis including mean, standard deviation, minimum and maximum values. In order to validate the data, we then queried the number of stations that were collecting weather data in Oahu. Finally, after determining the most active station we collected all the temperature observations from that station in the timeframe previously mentioned and plotted it on a graph. 

  After submitting our analysis to W.Avy, he has asked us for more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. From the same Oahu SQLite database, we will gather the requested weather data.

---
## Analysis
---
### Results:

  From our two statical analysis tables we produced from temperature data in the months of June and December we can observe the following:

  * The temperature data for both the months of June and December has a symmetrical distribution of data as the mean and median are almost identical. For       June the mean is 74.94 Fahrenheit and the median is 75.00 Fahrenheit and for December the mean is 71.04 Fahrenheit and the median is 71.00 Fahrenheit.
  * The month of June had almost 200 more temperature observations than the month of December; 1,700 compared to 1,517.
  * There aren’t many if not any outliers that are skewing the data for both the months of June and December as most data points are within 3 standard         deviations of the mean. The max values for both June and December, 85.0 and 83.0 Fahrenheit, are right outside of 3 standard deviations for both data       sets, 84.72 and 82.29 Fahrenheit.

June Temps                

![June_Temps](https://user-images.githubusercontent.com/99817571/164271616-4abd2b85-9630-44a3-9ffd-571d6f9d6499.png)

December Temps

![December_Temps](https://user-images.githubusercontent.com/99817571/164271644-c0399465-5c90-4d65-be59-3041a0215be8.png)

---
## Summary
---
### Recommendations

 There aren’t many if not any outliers that are skewing the data for both the months of June and December as most data points are within 3 standard deviations of the mean. The max values for both June and December, 85.0 and 83.0 Fahrenheit, are right outside of 3 standard deviations for both data sets, 84.72 and 82.29 Fahrenheit.

  The statistical analysis for the months of June and December supports our decision to locate the surf shop in Oahu. As we can see the change in temperature from the middle to the end of the year is relatively minimal as the mean temperature only dipped slightly from 74.94 to 71.04 Fahrenheit. Similarly, we can see that the temperature on a day-to-day basis remains in a very comfortable range as 95 percent of the temperature observations or 3 standard deviations for both months are; for June 65.16 to 84.72 Fahrenheit and for December 59.79 to 82.29 Fahrenheit. In order to validate our decision to locate our surf shop in Oahu we should conduct another query for precipitation levels in order to ensure that it is not raining to such an extent that customers will not show up year-round. Similarly, we should conduct another query for average wind speeds to help us determine the quality of surfing and the optimal hours of operation for the surf shop.

---
## Resources
---
Data Source: hawaii.sqlite

Software: Python 3.7.6, Jupyter Notebook 6.4.5
