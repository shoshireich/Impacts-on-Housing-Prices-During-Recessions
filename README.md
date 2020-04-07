# Impacts-on-Housing-Prices-During-Recessions
## Abstract
The hypothesis that the mean housing price in university towns was less affected by the 2008 recession than those in non-university towns is tested. United States GDP data is used to determine the exact quarters involved in the 2008 recession. Median home sale prices from the Zillow research data site is combined with a list of university towns across the country in order to compare the decline (or growth) of housing prices during the recession between the two different types of towns. The results of a t-test indicaute that the mean housing price in university towns did see reduced market loss. 

## Methods
The United States GDP over time in current dollars is evaluated to determine the financial quarters of the start, bottom, and end of the 2008 recession. Then, the university towns list is reformatted; state entries are extracted and the towns are grouped by state. The home sale prices data from Zillow is given in monthly intervals, so it is converted into quarterly intervals in order to be compatible with the GDP data. 

After the datasets are cleaned, the change of housing prices between the recession start and recession bottom is found for each town. A t-test is used to compare the university town values to the non-university town values. The mean price ratio of univeristy towns and of non-university towns is calculated using the formula: 

price ratio = (mean price at quarter before recession)/(mean price at recessionbottom)

## Results and Discussion
Mean Price Ratio of University Towns: 1.038
Mean Price Ratio of Non-University Towns: 1.052

With an alpha level of 0.01 and p-value of 0.004325, we reject the null hypothesis. This suggests that there is evidence to suggest that the mean housing price in university towns was indeed less affected by the 2008 recession compared to non-university towns. 
Additionally, university towns have a lower mean price ratio than non-university towns, indicating reduced market loss. 
