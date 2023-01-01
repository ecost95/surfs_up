# surfs_up

## Overview of the statistical analysis:
The purpose of this statistical analysis is to observe the temperature trends in Oahu in order to determine whether a surf shop will be profitable year-round. Specifically, we will be comparing all temperature data in the months of June and December from 2010-2017 to ensure that the conditions are favorable for our shop.

## Results:
We queried a SQLite file containing Oahu weather data to analyze trends in June and December. Our statistics summaries can be found below:

June Summary:
 -  ![June Summary](https://raw.githubusercontent.com/ecost95/surfs_up/main/June.PNG)
  
December Summary:
 -  ![December Summary](https://raw.githubusercontent.com/ecost95/surfs_up/main/December.PNG)
  
- Point one: Average temperature is high in both June and December. As we can see, the average temperature in June is 75 degrees, and the average temperature in December is 71 degrees. Although June may be slightly warmer, the weather stays hospitable year-round. 
  
- Point two: There is little variation in temperature between June and December - the standard deviations are 3.3 degrees and 3.7 degrees, respectively. This means that there would be few days with either very high or very low temperatures, meaning business would be steady. 
  
- Point three: There is more data overall in June (1700 temperatures) than in December (1517). The smaller sample size in December may affect on the accuracy of our results.
  
  ## Summary: 
Based on the reqults on our query, we would recommend opening this surf shop since the temperatures are consistent and temperate year-round. However, we do recommend two additional queries to boost the analysis:
  
- Query One: Analyze the percipitation in June and December to determine if the rain in Oahu is consistent. This should be a consideration as the rain will effect how many people will want to surf that day.

- Query Two: Analyze the max, min, and average temperature for all stations in a year. This will give use a more accurate snapshot of the climate in Oahu.
  
