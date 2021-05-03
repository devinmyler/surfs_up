# Surf's Up
Analyzing weather data with Flask

## Overview of analysis
Working with Temperature data to determine if a Surf and Ice Cream shop is viable year long. Using an sqlite file as out dataset, we created an app in flask to return queries, retrieving the recent temperature data from the months of June and December, then converted those queries into Pandas DataFrames, in order to graph that data using MatPLotLib.


## Results

![june_temps](https://user-images.githubusercontent.com/78869891/116829385-c59d3300-ab71-11eb-92f4-643e38c98f6b.png)![dec_temps](https://user-images.githubusercontent.com/78869891/116829386-c8982380-ab71-11eb-8a2b-1a0b97364168.png)

- June's average temperature was 74.9 degrees, December's was 71 degrees. There is not much differnce here. both above standard room temperature.
- The minimum temperature recorded for June was 64, in December it was 56. While the June low twmp should be fine for surf, it may not be the best case for selling ice cream, especially because there would likely be less tourists.
- However, these low temperatures do not occur very frequently. With a standard deviation of around 3 for both months, We know that the temperatures rarely fall too far from their mean. It will be consistenly temperate for a significant portion of the year.

# Summary 

Although the temperatures in June are, on average, nicer than december-- likely due to being located in the Northern Hemisphere-- neither month frequently records temperatures below what would be considered comfortable for selling ice cream or surfing. Though, temperature data isn't the be all end all when it comes to weather analysis. New queries could be run to determine precipitation, wind speed, or even cloudiness, as those factors would also go in to a decision about surfing or buying ice cream. Also, not all of those factors would contribute similarly to both.
The data we are working with does not contain the wind or cloud data, but when a query was run to find the amount of precipitation, this graph shows that it's not something that should be worried about.
![precipitation_overall](https://user-images.githubusercontent.com/78869891/116829931-dac79100-ab74-11eb-80a2-bf29bf195651.png)
