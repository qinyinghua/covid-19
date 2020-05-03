# Covid-19 Global Forecasting



## Dataset

The most popular data source is from JHU CSSEGI group, the Center for Systems Science and Engineering group in John Hopkin University.  The groups collect various data course and provide daily data update on their project github repository: https://github.com/CSSEGISandData/COVID-19. 

Kaggle has a covid-19 global forecasting contest in a weekly based.  In the Kaggle contest,  the group uses a further combined dataset based on JHU CSSEGI dataset - combine all daily csv files into one complete csv. Here is the Kaggle dataset: https://www.kaggle.com/imdevskp/corona-virus-report

JHU has a dashboard visualizing the worldwide/country/city number of cases. The map is using arcgis online system while the data is from JHU dataset.  https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6 

## Flatting the curve

We are currently at the middle of the Covid-19 pandemic.  When will this pandemic end? When should the country and state end the shelter-at-home order? At the statistic point of view, we are looking for "flatting the curve". We are looking for the curve of number of cases trending to flat instead of continue increasingly growth. 

## Does weather matter in this Covid-19 pandemic? 

In order to find out if the weather difference in countries/cities would impact the Covid-19 cases,  there are research adding the weather data into the covid-19 dataset for analysis. https://www.kaggle.com/davidbnn92/weather-data

Kaggle has a daily global dataset from worldwide weather stations. That is a BigQuery dataset which has no files to download but we can query it through the Google cloud BigQuery API. https://www.kaggle.com/noaa/gsod

Here is the weather data in the dataset. 

- `temp`: Mean temperature for the day in degrees Fahrenheit to tenths.
- `max`: Maximum temperature reported during the day in Fahrenheit to tenths--time of max temp report varies by country and region, so this will sometimes not be the max for the calendar day.
- `min`: Minimum temperature reported during the day in Fahrenheit to tenths--time of min temp report varies by country and region, so this will sometimes not be the min for the calendar day.
- `stp`: Mean station pressure for the day in millibars to tenths.
- `slp`: Mean sea level pressure for the day in millibars to tenths.
- `dewp`: Mean dew point for the day in degrees Fahrenheit to tenths.
- `wdsp`: Mean wind speed for the day in knots to tenths.
- `prcp`: Total precipitation (rain and/or melted snow) reported during the day in inches and hundredths; will usually not end with the midnight observation--i.e., may include latter part of previous day. .00 indicates no measurable precipitation (includes a trace).
- `fog`: Indicators (1 = yes, 0 = no/not reported) for the occurrence during the day



## References:

[1] Dataset: https://www.kaggle.com/imdevskp/corona-virus-report

[2] Kaggle contest: https://www.kaggle.com/c/covid19-global-forecasting-week-4/

