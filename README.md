# stats-fires

# Objective 
Do factors such as temperature, precipitation, wind speed, and seasonal patterns play a role in how frequent and severe wildfires occur? 

# Why
Wildfires in California have become increasingly destructive, burning millions of acres and threatening communities, ecosystems, and air quality. The underlying problem is the uncertainty about what environmental and climatic factors drive the largest fires. While Santa Ana winds, prolonged drought dry air, and record-breaking high temperatures are all known contributors, it remains unclear which factor (or combination of factors) plays the most significant role in fueling these extreme wildfires. We found interest in this topic as fires are something that continues to impact California and we are all currently residing in this state. 

# Dataset
We used 2 datasets:
* Wildfires Dataset: Data collected from fire incident reports recorded from CAL FIRE
* Weather Dataset: The data is collected from meteorological data from NOAA Climate Data Online with fire incident data from CAL FIRE

We merged these two datasets which included these variables:
Incident acres burned
Incident Date
Precipitation
Max Temp
Min Temp
Average Wind Speed

We found both dataset to be helpful for our research analysis and form a conclusion
Both Wildfire Dataset and Weather Data set were merged together and cleaned to be able to do visualizations and form conclusions 
SPSS was used to conduct descriptive analysis, correlation analysis, and regression analysis
The main focus of the study is to examine the relationship between wildfire burned areas and maximum temperature, average wind speed, and precipitation.

# Analysis
* Number of Fire by season shows that summer has the highest number of wildfires, making it the most fire-prone season.
* Fire size by season (boxplot, log-scale) demonstrates that autumn shows greater variability in fire size compared with summer. This is evident because the box (interquartile range) for autumn is taller than that for summer, meaning that the middle 50% of autumn fires span a wider range of sizes.

(inset image)

Descriptive Statistics
* Fire size (acres):
  * Mean ~ 4,602 acres,
  * Standard deviation very large (42,893), with a maximum of 1,032,648 acres → indicates extremely skewed distribution, with a few megafires inflating the average.
* Temperature (MAX_TEMP): Range 59–102°F, mean 74.4°F → most fires occur in warm/hot weather.
* Precipitation (PRECIPITATION): Mean only 0.003 inches → essentially zero, showing that most fires occur under dry conditions.
* Wind speed (AVG_WIND_SPEED): Mean 7.6 mph, range 0–15 mph.

Correlation Analysis:
* Fire size vs. temperature → weak positive correlation.
* Fire size vs. wind speed → weak positive correlation.
* Fire size vs. precipitation → almost no correlation (fires mostly occur without rainfall).

Regression Analysis
* Temperature vs. log fire size (Figure below): Using regression analysis, trend shows higher temperature associated with larger fires, but with high scatter → temperature matters but is not the sole determinant.
