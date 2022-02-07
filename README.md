# working_with_Matplotlib

## Overview of analysis
The purpose of this analysis was to analyze and visualize fares data across multiple city types in both a summary DataFrame and as a gridline graph depicting fares by week of time. This analysis works with understandings of the pandas module and how information can be organized as well as showing the capabilities and functionality of matplotlib visualizations.

## Results

### PyBer Fares Summary:
![PyBer Summary](https://github.com/drewabramo12/working_with_Matplotlib/blob/main/Resources/PyBer_summary_df.PNG)

As seen in the image above, PyBer fares vary based on city type. A running theme that can be seen is the the population size has an effect on fares. Urban cities show a higher number of drivers as compared to Rural cities. Urban cities also seem to have a higher quantity of rides compared to suburban and rural cities which also follows the same trend respectively. There seems to be a higher quantity of drivers than rides within in urban areas and that would mean that a certain population of drivers have never completed a ride. This data may need to be cleaned to see a more accurate idea of what an average fare per driver actually is. Higher quantities of moneyare collected in With the average fares of ride and driver, less populated areas have higher fares than more populated areas. This data can mean that the distances traveled with rural and suburban areas are longer than that of urban areas but, more research would be be needed to come to any conclusions on this matter.

#### Challeges


### Total Fares by City Type Plot:
![PyBer line graph](https://github.com/drewabramo12/working_with_Matplotlib/blob/main/analysis/Pyber_fare_summary.png)

The line graph depicts the fares collected on a week by week basis from January through February. There seems to be a consensus within the line graph and the summary showing that sums of the fares increase based on city type/population size. There is a uniform peak in the 4th week of February. The data also shows that as the year continues the amount of fares collected increases. This implies that more rides occur on week by week base as the year continues.

## Summary
As mentioned above and repeated here, urban cities seem to generate the most revenue. Urban cities, however, seem to have a significant population of drivers that have never actually given a customer a ride. This could be an avenue to investigate to incentivise drivers to be both more active and to encourage more customers to lean into using PyBer as a resource. The fourth week of february has a high level of commerce for pyber compared to other weeks in the first third of the year. Promotions could be run to increase the desirability of the PyBer platform during this time. As a final recommendation. Rural areas have much fewer rides and much higher fares than suburban and urban areas. This can make paying for rides more challenging and cause customers to not use PyBer as much. Looking into whether giving discounts for rides in rural areas maybe worthwhile as well.