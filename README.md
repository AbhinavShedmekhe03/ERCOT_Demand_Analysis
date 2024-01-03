# ERCOT Electricity Demand Analysis

## Aim
The aim of this project is to analyze and explore the electricity demand data for different regions within the ERCOT (Electric Reliability Council of Texas) system. The project covers the years 2018, 2019, and 2020, with a focus on understanding the temporal patterns, correlations between regions, and overall trends in electricity demand.

## Process Followed
The project followed a structured process to achieve its objectives:

1. **Data Collection:**
   - Three separate datasets for the years 2018, 2019, and 2020 were imported into a Jupyter Notebook using pandas.

2. **Data Concatenation:**
   - The datasets were concatenated to create a consolidated dataframe (`df`) that spans all three years.

3. **Data Cleaning:**
   - The 'HourEnding' column was cleaned to replace '24:00' with '00:00' and remove additional information like " DST."
   - The 'HourEnding' column was converted to datetime format.

4. **Data Exploration and Visualization:**
   - Descriptive statistics were computed to understand the basic characteristics of the dataset.
   - Time series graphs were plotted to visualize electricity demand trends over time.
   - A correlation matrix was generated and visualized using seaborn.

5. **Peak Demand Analysis:**
   - Peak demand regions for each hour were identified and visualized.

6. **Hourly Analysis:**
   - Average electricity demand by the hour of the day was analyzed and visualized.

7. **Yearly Comparison:**
   - Total electricity demand across regions was compared on a yearly basis.
