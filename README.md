# PyBer Analysis

## Overview
After being hired by PyBer, a Python based ride sharing app company, I was asked to perform an exploratory analysis on data in two csv files. With the help of Omar and Sasha, I created several types of visualizations to tell a compelling story about the data, that I will present to the CEO of PyBer, V. Isualize. While working on the presentation, I wrote Python scripts using Panda's libraries, the Jupyter notebook, and Matplotlib to create a summary DataFramce and a variety of charts that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city. 

## Purpose
The purpose of this analysis was to highlight the differences between different city types and how these types affect Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. By breaking down each ride into the three city types, the tendencies become more clear which allows better decisions to be made. The analysis and visualizations that are presented to V. Isualize will help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods.

### Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Anaconda Prompt (Python Data), Jupyter Notebooks
- Dependencies: Pandas, Matplotlib

## Results
The following DataFrame gives a summary of the three city types: Urban, Suburban, and Rural:

![PyBer_Summary_DataFrame](https://user-images.githubusercontent.com/109091887/187668394-d8cbce74-f37a-470f-ad7b-91da20dbf44f.PNG)

A quick look at the table tells you that urban cities tend to have more total rides, total drivers, and total fares; whereas rural cities have greater averages fares per ride and per driver. This data is powerful but using visual representations give the ability to see a much more detailed breakdown of the data.

Below are three side-by-side boxplots that represent the central tendencies of Ride Count, Ride Fare, and Ride Driver data. These boxplots allow for a more complete picture compared the table and allow the viewer to make clear comparisons between the city types. We now *see* what was previously described in that urban cities tend to have more riders, drivers, and fares; but the boxplot includes the minimum, 1st quartile, median, 3rd quartile, maximum, and outliers of each city type, giving the view a more well rounded undertanding of the data.

**Figure 1**

![Fig2](https://user-images.githubusercontent.com/109091887/187673278-b3f5a16e-92bd-4738-8ca3-5d1d39e3b03d.png)

**Figure 2**

![Fig3](https://user-images.githubusercontent.com/109091887/187673291-931619d7-8ac1-4494-8a0e-c49befbd8e52.png) 

**Figure 3**

![Fig4](https://user-images.githubusercontent.com/109091887/187673304-2d87a72b-efc1-4a16-b7cf-fd06ed6fc593.png)

The use of pie charts are an effective way to show the portion a piece of data represents compared to the whole. In the summary DataFrame, finding the largest total rides, total fares, and total drivers was easy but the pie chart quickly shows how much each of those represent compared to all rides, all fares, and all drivers. Below are three pie charts that represent the porportionality of each city type to all cities, with respect to fares, rides, and drivers. 

**Figure 4**

![Fig5](https://user-images.githubusercontent.com/109091887/187676999-a304ec7f-b988-4898-b1ab-5981c4acdec8.png) 

**Figure 5**

![Fig6](https://user-images.githubusercontent.com/109091887/187676285-9b28c072-1714-4051-a58b-f1aa1c49a5ea.png)

**Figure 6**

![Fig7](https://user-images.githubusercontent.com/109091887/187676303-dab679fc-a22f-4128-83a3-b049b4c4d500.png)

Boxplots and pie charts are strong graphs that show central tendencies and proportion to the whole, respectively, but using a sophisticated graph will be a more efficient way to incorporate multiple variables into a visually appearing and purposeful chart.

**Figure 7**

![Fig1](https://user-images.githubusercontent.com/109091887/187671010-437e19b4-e5bd-4b5f-beab-9c05211da5f8.png)

In the bubble chart in the figure above, we now can see the tendencies that were described above as well as each specific city and the overall trend that occurs between the different city types and fares and drivers. Each bubble represents a city within the data. Each city is plotted based on Average Fare as the y-axis, Number of Rides as the x-axis, as well as using the size of the bubble to represent the Number of Drivers. It is now much more clear that rural cities have high average fares and lower number of rides, compared to urban cities which have lower average fares and higher number of rides. Also, due to the graph including the different sizes of bubbles, rural cities tend to have less drivers (small bubbles) and urban cities tend to have more drivers (larger bubbles). 

Lastly, it can be beneficial to observe and compare data across a specific time frame. By using a multi-line graph, comparing the total fares for each city type is quick and easy. This will allow us to determine if there are certain trends during specific times of the year for each city type or if they preform similarly regardless of their city's density. Using the figure below, we observe that on a weekly basis, urban cities have the most total fares from beginning of January to the end of April. Each city type had a steady increase with a first peak in the third week of February, so it may be beneficial to look into why all city types preformed well during that specific week. 

**Figure 8**

![PyBer_fare_summary](https://user-images.githubusercontent.com/109091887/187682364-23986f0d-51ac-484f-a28e-826de8d43f9d.png)

## Summary
The data and it's visualizations have allowed for many observations to be made. Based on these observations I recommend the following:
1. 
