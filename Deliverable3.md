# Module 9 Challenge

## Overview of the analysis: 
This analysis is for W. Avy using advance data storage and retrieval in Jupyter notebook, SQLite and SQLAlchemy to examine temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. Deliverable 1 is to Determine the Summary Statistics for June and Deliverable 2 is to Determine the Summary Statistics for December.

## Results: 
### Three major points from the two analysis deliverables:
- The average recorded temperature in June is about 75 degrees F and in December is about 71 degrees F, June is 4 degrees higher than the average temp in December. This represents a -5% change in average temperature from June to December
- The minimum temperature recorded in June is a lot higher than in December, June's min is 64 degrees F and December's min is 56 degrees F with reperesents a -8% change in min temperature from June to December. 
- The December temperatures seem to be more variable than those in June given its larger range in recorded temperatures (comparing the max vs min temp of each month). However, when looking at the distribution of Dec Temps, we can see that the median temperature in Dec is more inline with the average, and there are not many outliers skuing the average temperature higher or lower than the actual recorded frequency.

![alt text](https://github.com/lyozamp/surfs_up/blob/main/June_Temp.png) 
![alt text](https://github.com/lyozamp/surfs_up/blob/main/Dec_Temp.png) 

## Summary: 
I would summize that even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees and December's median temperature, with the highest frequency recorded across a span of years, is about 72 degrees, at least double the frequency of the next highest recorded temperatures, 75 and 67 respectively. It would be ill advised to not open the surf and ice cream shop based on at first clance temperature minimums.

### Before recommending a final deicision though, I would want to perform some additional queries to get more information on weather conditions in these two months:
1. For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.
2. Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Sunch varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business.
