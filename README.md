# Anurag-capstrone-ds
# BUS ARRIVAL AND WAITING TIME ANALYSIS

## 1. Project Overview
This project focuses on analysing public transport bus data to understand bus arrival patterns, travel time, speed, and congestion levels. The main aim is to use data analysis techniques to study bus services and identify patterns that can support better public transportation planning.

## 2. Problem Statement
Public transportation users often face uncertainty regarding bus arrival times and waiting periods. This project analyses bus-related data to understand arrival patterns, travel time, and congestion. It aims to provide useful insights that can help improve bus schedule monitoring and transport management.

## 3. Objectives
- To analyse public transport bus data.
- To understand bus arrival patterns.
- To study bus speed and travel time.
- To examine route and congestion information.
- To identify hourly bus activity patterns.
- To represent data through graphs and visualisations.
- To support better transportation planning through data analysis.

## 4. Dataset Description
The project uses a public transport bus dataset containing **66,913 records and 9 original columns**.

The dataset includes:
- Stop ID From
- Stop ID To
- Trip ID
- Arrival Time
- Time
- Speed
- Number of Trips
- SRI
- Degree of Congestion

This information helps in understanding different aspects of bus transportation.

## 5. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 6. Methodology
The project follows these major steps:

1. **Data Collection:** Loading the public transport dataset into Google Colab.
2. **Data Exploration:** Understanding dataset structure, columns, data types, and statistical information.
3. **Data Cleaning:** Checking duplicate records and handling missing values.
4. **Statistical Analysis:** Examining numerical and categorical variables.
5. **Data Visualisation:** Using graphs, bar charts, and a correlation heatmap to understand patterns.
6. **Time-Based Analysis:** Studying bus records according to different hours of the day.
7. **Conclusion:** Interpreting the findings and providing recommendations.

## 7. Key Observations
- The original dataset contains 66,913 records.
- No duplicate records were found.
- Missing values were identified and handled during data cleaning.
- The cleaned dataset contains zero missing values.
- The dataset includes four congestion categories.
- The highest number of bus records was observed at 2 PM, with 39,460 records.
- A total of 14,338 records were observed at 9 AM and 13,115 records at 6 PM.
- The correlation heatmap shows a moderate positive relationship between starting and ending stop IDs.

## 8. Limitations
The dataset does not contain a separate arrival delay column. Therefore, exact bus arrival delays and passenger waiting times could not be calculated. Actual passenger waiting time would require additional information about passenger arrival times and bus service frequency.

## 9. Recommendations
- Improve bus schedule monitoring.
- Monitor bus arrival patterns during different hours.
- Study congestion levels on different routes.
- Improve transportation planning using data analysis.
- Collect additional delay and passenger waiting-time information for more accurate future analysis.

## 10. Conclusion
This project demonstrates how data analysis can be used to understand public transportation patterns. The dataset was explored, cleaned, and analysed using statistical techniques and visualisations. The hourly analysis showed that 2 PM had the highest number of bus records. The project provides useful insights into bus arrival patterns, speed, travel time, and congestion. These findings can support better bus schedule monitoring and transportation management.

## 11. Future Scope
In the future, this project can be improved by including real-time bus tracking, actual arrival delay information, passenger waiting-time data, and machine learning techniques to predict bus arrival times.
