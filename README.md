# Surfs_up_Analysis

## Overview of the analysis:

In this project we are creating Flask application to find out the temperature conditions in June and December if favorable for surfing and ice creams for tourists so that W.Avy can take decision to invest in the Surf and shakes shop.
In this project we need to deliver below deliverables for the analysis Using Python, Pandas functions and methods, Flask and SQLAlchemy, filtering the date column of the Measurements table in the hawaii.sqlite database to retrieve all 
the temperatures for the month of June & December and converting the temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Deliverables

1. Summary Statistics for June

2. Summary Statistics for December

3. A written report for the surfs_up analysis (README.md)

	
### Software Used
python- 3.9.7 , conda 4.10.3, jupyter 1.0.0, SQLAlchemy

## Results:

### June_Month

1. The statistical analysis is providing us a summary of different statistics for the number of temperatures in June month. The count (1700) is the number of times temperature was observed for June month.

2. The mean temperature is 74.94 and Standard deviation for June month is 3.26 it means most of the temperature in June falls between 78.2 and 71.68.
3. The 75% of time temperature is 77.00 and max temperature is 85.00 which is good temperature for surfing and ice-creams.

Below showing statistics and plots for June

![](https://github.com/sumanpriyah/surfs_up/blob/main/Resources/June_temp.png)

![](https://github.com/sumanpriyah/surfs_up/blob/main/Resources/June_temp_plot.png)


### December_Month

1. The statistical analysis is providing us a summary of different statistics for the number of temperatures in December month. The count (1517)is 
the number of times temperature was observed for December month.
2. The mean temperature is 71.04 and Standard deviation for December month is 3.75 it means most of the temperature in December falls between 
between 74.79 and 67.29.
3. The 75% of time temperature is 74.00 and max temperature is 83.00 which is good temperature for surfing and ice-creams

Below showing statistics and plots for December

![](https://github.com/sumanpriyah/surfs_up/blob/main/Resources/December_temp.png)

![](https://github.com/sumanpriyah/surfs_up/blob/main/Resources/Dec_temp_plot.png)

## Summary:

Below are the Querys and result attached where precipitation for June and December are calculated. The minimum precipitation for June and December are 0.
75% of the time for both months are very close 0.12(June) and 0.15(December). Both June and December have similar and very close weather conditions.
Weather conditions are favorable for both surfing and Ice cream store and seems good investment.

![](https://github.com/sumanpriyah/surfs_up/blob/main/Resources/June_Dec%20_precipitaion.png)
