# Surfs Up
## Overview
W. Avy has requested an analysis of the June and Decemnber temperature data for Oahu in order to determine if it is feasible and sustainable to open a surf-and-ice-cream shop year-round. There are two deliverables:
1) Summary Statistics for June
2) Summary Statistics for December

Both are created from temperatures retrieved (via filtering) from "Measurements" table in the hawaii.sqlite database that have then been converted to a list and then a DataFrame for generating summary statistics.

Tools used:
* Python
* Pandas
* SQLAlchemy

## Results
### Code:
[SurfsUp_Challenge.ipynb](https://github.com/lexyzhong/surfs-up/blob/main/SurfsUp_Challenge.ipynb)

### Summary Statistics for June
![June-Temps.png](https://github.com/lexyzhong/surfs-up/blob/main/Resources/June-Temps.png)

In June, the mean temperature was 74.9°F, median was 75.0°F, with a low of 64.0°F and high of 85.0°F, generated from a total of 1700 data points.

### Summary Statistics for December
![December-Temps.png](https://github.com/lexyzhong/surfs-up/blob/main/Resources/December-Temps.png)

In December, the mean temperature was 71.0°F, median was 71.0°F, with a low of 56.0°F and high of 83.0°F, generated from a total of 1517 data points.

## Summary
* Based on the temperature data, it is generally warm enough in Oahu during both the Summer and Winter seasons for there to be expected demand for surfing and ice cream consumption. The data suggest that an surf-and-ice-cream shop business should be sustainable year-round.
* However, additional weather analyses may be of interest. Other factors such as precipitation, humidity, cloudiness, and winds may affect consumer interest in surfing and ice cream consumption.
