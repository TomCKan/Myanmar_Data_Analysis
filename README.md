# Myanmar_Data_Analysis

Exploratory data analysis of deaths caused by ongoing conflicts in Myanmar using data from The Uppsala Conflict Data Program (UCDP).



## Myanmar Data Analysis Initial Questions

Questions and hypothesis I am looking to get more insight to through exploratory data analysis:

- How much have conflict related deaths increased or decreased over the past 20 years? The country has never been a unified state and large areas of the country remain as rebel held territory. Conflict has erupted continuously for the past century but more recent conflicts I’m interested to find out about are the forced removal and genocide of Rohinga minorities in 2017, and the expected escalation in conflicts between armed groups since the 2021 coup d’etat.
- Are there significant differences in conflict related deaths between government held areas and contested territory? And if there is, does it coincide with major events e.g. the 2021 coup?
- Is data from ACLED and UCDP datasets significantly different? And do these datasets give similar answers to each other in relation to the previous questions?

These questions will give us a more in-depth knowledge about the conflict, and the data relating to it.



## Myanmar Death Figures Data Analysis

After cleaning the data from UCDP there were several key findings that relate to recent conflicts. 
When looking at the deaths per day and deaths per month caused by conflict, there have been conflicts occurring on and off since records began. There have not been any long periods of peace which show how unstable this 'country' really is. Below we can see all the data UCDP has on deaths caused by conflict in Myanmar.

![](https://github.com/TomCKan/Myanmar_Data_Analysis/blob/main/images/bokeh_plot%20(1).png)


If we take a closer look at the right of the graph (below), we can see a significant increase in deaths on a daily & monthly level. This period of violence from 2021-2022 coincides with the coup, and shows that conflict events in Myanmar are happening on a daily basis; likely as a result of removal of the few democratic freedoms they had in the first place.

![](https://github.com/TomCKan/Myanmar_Data_Analysis/blob/main/images/bokeh_plot%20(2).png)


When we look at the specific actors involved in the conflicts, we can see that historically most deaths are overwhelmingly civilians. Other than the Government of Myanmar, we can also see there are a large number of armed organisations (majority of which have been fighting the Government for decades). 
In the following graph we can see one month where a very high number of civilians were killed. This would be the 2017 Rohingya genocide which was carried out by the Government. UCDP has already stated that the real death figures are likely to be much higher, as they only include figures of individual events that have been verified by several sources.

![](https://github.com/TomCKan/Myanmar_Data_Analysis/blob/main/images/bokeh%20lineplot%20all%20actors%20per%20month.png)


We can look into this further and look at the average number of deaths from conflicts per month, which is an indicator of which times of year have the most conflicts, the higher the number of deaths, the higher the number of conflicts. What we can see from the median is that on average, August is one of the months with the fewest number of conflicts; there are reports that weather and season can be a cause of this. August is also when the 2017 Rohingya genocide occurred (which is why the mean is so much higher). Given that the Government is involved in so many continuous conflicts, this data suggests that the Government intentionally chose this month to start this genocide. Probably because it meant they could reallocate resources to Rakhine State (where this genocide took place), as there were less conflicts occurring elsewhere in the country. This suggests that this was not just another conflict that escalated, but a premeditated strategic action which required planning.

![](https://github.com/TomCKan/Myanmar_Data_Analysis/blob/main/images/Average%20deaths%20per%20month%20barchart.png)



