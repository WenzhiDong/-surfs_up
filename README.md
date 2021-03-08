# SurfsUp_Challenge

## Overview
I will open a surf n' Shake Shop serving surf boards and ice cream to local in Hawaii. My investor, W.Avy, concerns about the weather and wants me to do some analytics on it. 
I will Sqlalchemy module in Python to query the data From a SQLite database to find the temperature data for the months of June and December in Oahu, 
in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
![june](/Resources/june.png)
![dec](/Resources/dec.png)

 - The average temperature in June is a little higher
 - The temperature variation in June is smaller, because standard deviation is lower  
 - The minimum and maximum temperature in June are both higher than those in December

## Summary

### June vs. Dec Precipitation Summary
![june](/Resources/june_prcp.png)
![dec](/Resources/dec_prcp.png)

### June vs Dec: Precipitation Average Over 7 years 
![juneAvg](/Resources/june_prcp_avg_change.png)
![juneAvgPlot](/Resources/june_prcp_avg_change_plot.png)


![decAvg](/Resources/dec_prcp_avg_change.png)
![dec_avg_plot](/Resources/dec_prcp_avg_change_plot.png)

### Conclusion
 - Temperature difference is not very large, temperature would not affect the business
 - Percipitation is larger on Dec than June, which may affect the business of the store on Dec.
 
 Although precipitation is larger on Dec, recent years, the percipitation over time is actually decreasing and become more stable on Dec than June, from the line plot. 
 
 In other words, in some years, precipitation on June may become larger than Dec and affect the business on June, while most of time, precipitation would larger on Dec.    

The business would not meet big problems over time, but will have a little less profit on Dec.
