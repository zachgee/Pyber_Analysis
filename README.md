# Pyber_Analysis

## Overview

For this project, we were approached by a frined, V. Isualize, to help him analyze data pertaining to the rideshare app, Pyber. V. Isualize asked us to compare the number of rides, number of drivers, total revenue from fares, the average fare of a ride and the average fare per driver based on the citites population (cites were categozied by "rural", "subruban" and "urban." Secondly, V. Isualize wanted to see the total of the fares from rides by city type. To help V isualize, we utilized Python and Pandas to create dataframes and graphs to help V. Isualize understand the data. 

## Resources

  - city_data.csv
  - ride_data.csv
  - Python 3.7.6, Jupyter Notebook

## Results

![Summary_df](https://user-images.githubusercontent.com/87949792/144764727-2203b6ae-8612-4d2a-8227-9fca44f91de8.png)

The dataframe created shows that rides, drivers and fares all increase as a city becomes more populated. On the otherhand, average fare per ride and average fare per driver decrease as a cities puplation increases.

![PyBer_fare_summary](https://user-images.githubusercontent.com/87949792/144764785-e2382fe9-af7b-4877-b1c6-2f6d127474cc.png)

The linegraph shows the total fares by week for each city type. It appears that there is a steady fluctuation, each city type has their good and bad weeks but overall they stay on a steady line with no obvious upward or downward slope. Rural cites constantly genereate the lowest fares, suburuban is in the middle and urban at the top. The suburban line does end on an interesting note, increasing as the urban line sees a slight decrease. More data will be needed to see if this trend continues or if it is just a good month for suberban drivers. 

## Summary

The results seem somewhat intuitive. We can see that Urban areas generate the most fares over all, but also provide the cheapest rides and least fare per driver. There is more demand in urban areas, however there is also likely a much higher supply for drivers. Drivers may flock to urban areas in order to make more money, however they are making less money per ride. Serveral other factors play into this of course, for example the length of a trip in an urban setting may be on average shorter than the length of an average trip. Based off of the findings, the following recommendations are given in order to help both Pyber, Pyber costumers and Pyber drivers. Creating a tiny bit (don't go overboard) of scarcity in the urban setting will help balance out the fares between the settings. 

  - 1) Incentivize more drivers to work in rural settings (But not too many). Sending some drivers into rural areas will bring down fares for customers, and give drivers a chance to make more money per ride. However, be careful not to flood the rural areas.
  - 2) Focus in on the subrban market. It seems that the suburban market has the most obvious upward trend. Let drivers know that the subrban market is growing and there is money to be made providing subruban rides.
  - 3) Try to de-flood the urban area of some drivers. The urban setting will always need more drivers due to higher demand, but right now the balance between the three settings is way off. If left unchecked, drivers will not make any money in urban settings, leading to unhappy workers and more likelihood of drivers quitting. 
