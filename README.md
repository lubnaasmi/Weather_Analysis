# Coffee Production & Weather Impact Analysis


Welcome to my TLAB submission for Coffee Production and Weather Analysis!
This project explores the relationship between weather conditions and coffee productivity using real-world agricultural data. It walks through the process of analyzing temperature, rainfall, humidity, and wind speed to understand their impact on yield and tree density. Built as part of our TLAB assignment, the project combines statistical analysis and visualization to provide actionable insights for improving coffee farming outcomes.

## Data Dictionary

Column descriptions for each dataset is listed below:

**weather_data**

This dataset describes yearly weather outcomes for the coffee-growing months of Minas Gerais. Only weather data from January through May is considered.

* year: Year on which metrics were calculated. 
* rain_max: Average maximum millimeters of rain.
* temp_avg: Average temperature in celsius.
* temp_max: Average maximum temperature in celsius.
* temp_min: Average minimum temperature in celsius.
* hum_max: Average maximum humidity in percentage.
* hum_min: Average minimum humidity in percentage.
* wind_max: Average maximum wind speed in meters per second.
* wind_avg: Average wind speed in meters per second.
* subdivision: Name of Brazilian sub-division (all should be Minais Gerais)

**coffee_output**

This dataset describes yearly features related to the coffee harvest that begins in June and ends in September in Minas Gerais.

* country: Country where harvest occurs (all should be Brazil).
* subdivision: Name of sub-division (all should be Minais Gerais)
* type: Type of coffee bean
* 60kgs_bag: 60 kg bags of coffee beans harvested (million bags)
* year: Year of harvest
* nonbearing_trees: Amount of nonbearing coffee trees (million trees)
* bearing_trees: Amount of bearing coffee trees (million trees)
* nonbear_hectares: Hectares of nonbearing coffee trees (thousand hectares)
* bearing_hectares_per_hectare: Average number of bearing trees per hectare
* nonbearing_trees_per_hectare: Average number of non-bearing trees per hectare

## Objective

To determine how different weather conditions, such as wind, humidity, temperature, and rainfall affects coffee production performance indicators, using statistical correlation and visual analysis.


## Methods Used

- **Pearson correlation analysis**
- **Seaborn heatmaps and scatter plots**
- **Descriptive statistical interpretation**
- Python libraries: `pandas`, `matplotlib`, `seaborn`


## Key Findings

- **Wind speed** has the **strongest negative effect** on yield and tree density:

- **Minimum humidity** and **Average temperature** also show **moderate negative correlations** with tree count and productivity.

- **Maximum rainfall** shows a **weaker but still negative** relationship with yield.



## Next Steps

To further explore the impacts of weather and economic forces on coffee production, I would collect data on solar radiation, soil quality, irrigation practices, water availability, planting density, and tree age distribution, as these directly affect crop growth. Economically, I’d gather information on market prices, input costs, subsidies or incentives, labor availability and wages, export volumes and prices, and transportation, as these factors influence production decisions and profitability.



## Conclusion

> *From the above data analysis, the most favorable conditions for coffee growing include low wind speeds, moderate humidity, mild temperatures, and balanced rainfall. Wind stands out as the most harmful factor, showing strong negative correlations with yield (60kgs_bag). This means that protecting coffee plants from strong winds, through windbreaks or natural barriers, should be a top priority. Additionally, managing humidity and avoiding temperature extremes can help reduce disease risk and maintain tree health. Overall, focusing on these environmental factors can lead to healthier plantations and improved coffee productivity.*
