## Part 1: Analysis of access to safely managed sanitation services

### Prerequisites
This analysis was ran using the following configuration:
- _Python version_: 3.8
- _Packages versions_: pandas==1.2.0 | numpy==1.19.4 | wbdata==0.3.0 | datetime==4.3
plotly==4.14.1 | statsmodels==0.12.1

### Objective
The objective of this analysis is to identify changes and time trends in access to safely managed sanitation services, including variations in access levels by income group, using plotly for visualization.

### Data sources
- World Development Indicators database for access to sanitation data
- World Bank Country and Lending groups classification database for income groups data

### Workflow
The pipeline is fully automated, using inputs available through APIs or webscraping. Therefore, paths do not need to be modified.

### Author
Alex Chunet

## Part 2: How long do World Bank retirees live?

There are several several biases and erroneous interpretation which make the claims in the email ultimately unreliable. Here are the main issues:
1)	 The two samples considered are not comparable due to different selection criteria. Indeed, while the data about average life expectancy in the US only considers individuals above 65, the World Bank retirees sample includes a significant amount of observations for people younger than 65. The direct consequence of this difference in selection method is that the national level data will naturally tend to display a higher mean (which is the case here) due to a higher cutoff. Therefore the statement of the author (“This is not very impressive etc.”) is based on an erroneous interpretation of the data.
2)	The characteristics of the World Bank retirees sample also point out to possible data quality issues. Indeed, the sample includes observations for ages as low as 54 years old which seems an unrealisticly young age for retirement. Therefore, there would be a need to double check the quality of the data.
3)	Finally, if the cutoff at 65 years of age is applied, the author would still need to verify that both samples have been collected over the same period of time. The World Bank retirees data is focusing on deaths “within the past 6 years”. However, there are no indications on the timeframe used for the national level life expectancy estimates. 
4)	Besides those methodological issues, we could also argue that the use of the US life expectancy data as a comparator is not adapted to the international dimension of the World Bank. Indeed, a significant share of the World Bank staff lives in other countries and especially in developing countries where life standards, public services and environmental conditions are very different from the US. This dimension could be taken into account through the use of a weighted average life expectancy representative of the location of either World Bank staff or World Bank retirees geographical location.

