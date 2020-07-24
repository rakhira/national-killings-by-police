# National Killings by Police
---
This project is aimed at investigating:
1. The role that racism plays in the way BIPOC who are killed by police are ‘coded’ in terms of armed status.
2. To investigate the relationship between city police spending and city police killings, especially of BIPOC.


## EDA
---
I spent most of time doing EDA of my second dataframe, which was a merger of the Mapping Police Violence dataset on '2019-2019 Killings by PD' and the Lincoln Institute's 2013-2019 data on city budgets. In total, there were 78 cities represented in the dataset, based on which cities had police killings that had been reported on from 2013-2019. 

![](img/diss_index_police_spending_Black_hom_rate)

![](img/diss_index_police_spending_violent_crime_rate)

![](img/police_spending_vs_hom_rate_4_plots)

![](img/police_spending_vs_hom_rate_by_race)

## Reflection
---

Even though I was unable to reject my null hypothesis that the ratios of unarmed killed who are BIPOC and unarmed killed who are white are the same, I still enjoyed the research and skill building that this project involved. I was able to deepen my Pandas knowledge as well as my ability to plot using Matplotlib. 

In the future, I would perhap pick a dataset that is more standardized, and more localized, as my domain knowledge is deeper when it comes to systems-based studies on the local and state levels. Not knowing whether the Mapping Police Violence dataset was complete or not (and not having an official national database of police killings) made it hard to fully understand what I saw in EDA and my hypothesis testing.

If I had time, I would have like to generate plots for every column of spending in the Lincoln Institute dataset versus every metric of police killings in the Mapping Police Violence dataset to determine which combination of factors/metrics do have strong correlations.

## References
---
1. https://mappingpoliceviolence.org/s/MPVDatasetDownload.xlsx
2. https://www.lincolninst.edu/research-data/data-toolkits/fiscally-standardized-cities/search-database
