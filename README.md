# Weather-Dataset-Analysis

This project analyzes historical weather data to uncover trends, patterns, and insights such as temperature changes, fog patterns, and dangerous visibility levels.

##  Dataset Columns

The dataset includes the following columns:

- `Time_H`: Hour of the day (0–23)
- `Temp_C`: Temperature in Celsius
- `Dew Point Temp_C`: Dew point temperature
- `Rel Hum_%`: Relative humidity in %
- `Wind Speed_km/h`: Wind speed in km/h
- `Visibility_km`: Visibility in kilometers
- `Press_kPa`: Atmospheric pressure
- `Weather`: Weather condition (e.g., Fog, Rain, Snow)
- `Day`, `Month`, `Year`: Date information

##  Project Goals and Tasks

| **Goal**                        | **What You Should Do**                                                                                                       |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
|  1. Clean the Data            | - Remove or fill missing values (e.g., in `Visibility_km` or `Weather`) <br> - Convert `Date/Time` to datetime format        |
|  2. Understand the Data       | - Show basic stats: mean, min, max, etc., for each numeric column <br> - Count how many times each weather condition appears |
|  3. Visualize the Trends      | - Plot temperature over time <br> - Show how humidity or wind speed changes in a day or month                                |
| 🌦 4. Analyze Weather Patterns | - When was the fog most common? <br> - What kind of weather is linked with low visibility or high humidity?                  |
| 🕰 5. Group Data by Time       | - Group by day/month to see average temperature, humidity, etc. <br> - Find out which month had most fog or rain             |
|  6. Detect Extremes & Alerts  | - Detect times when visibility dropped below 1 km (possible danger/alerts)                                                   |

##  Key Visualizations

- Line plot of temperature over time
- Pie chart of weather condition frequencies
- Heatmap: Average hourly temperature per day


##  Tools Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

##  Insights You Can Gain

- Weather patterns across different months
- Fog and freezing fog frequency analysis
- Times when visibility was dangerously low
- Relationships between temperature, humidity, and pressure



