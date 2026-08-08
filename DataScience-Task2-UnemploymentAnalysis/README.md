# Task 2: Unemployment Analysis with Python

## Internship Program
AICTE Oasis Infobyte Internship Program

## Track
Data Science

## Objective

The objective of this project is to perform exploratory data analysis on unemployment data in India to identify regional and temporal trends, with a particular focus on changes in unemployment during the COVID-19 period.

## Dataset

The dataset used in this project contains unemployment-related information for different regions of India.

The dataset contains information about:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

After cleaning the dataset, 740 records and 7 columns were available for analysis.

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning

The following data preparation steps were performed:

1. Loaded the unemployment dataset.
2. Inspected the number of rows and columns.
3. Checked column names and data types.
4. Checked for missing values.
5. Cleaned the column names.
6. Removed records containing missing values.
7. Converted the Date column into datetime format.
8. Verified the updated data types.
9. Confirmed that no missing values remained after cleaning.

After cleaning, the final dataset contained:

- 740 rows
- 7 columns
- 0 missing values

## Exploratory Data Analysis

The analysis included:

1. Dataset shape and structure inspection.
2. Missing value analysis.
3. Descriptive statistics.
4. Region-wise average unemployment rate analysis.
5. Month-wise unemployment trend analysis.
6. Time-series analysis of unemployment rates.
7. Comparison of unemployment trends across major regions.
8. Bar chart analysis of regions with high average unemployment rates.
9. Correlation analysis between unemployment rate, employment, and labour participation.
10. Pre-COVID and COVID-period comparison.

## Region-wise Unemployment Analysis

The average unemployment rate varied considerably across different regions.

Based on the calculated regional averages:

- Tripura had the highest average unemployment rate at approximately 28.35%.
- Haryana had an average unemployment rate of approximately 26.28%.
- Jharkhand had an average unemployment rate of approximately 20.59%.
- Bihar had an average unemployment rate of approximately 18.92%.
- Himachal Pradesh had an average unemployment rate of approximately 18.54%.

The analysis showed differences in unemployment levels across regions in India.

## Pre-COVID vs COVID Period Comparison

The project compared the average values between the Pre-COVID period and the COVID period.

| Metric | Pre-COVID | COVID Period |
|---|---:|---:|
| Unemployment Rate (%) | 9.509534 | 17.77436 |
| Estimated Employed | 7,466,028 | 6,517,203 |
| Labour Participation Rate (%) | 43.88612 | 39.33005 |

The comparison shows that the average unemployment rate increased from approximately 9.51% during the Pre-COVID period to approximately 17.77% during the COVID period.

At the same time, the average estimated employment decreased, while the average labour participation rate also decreased during the COVID period.

## Key Observations

- Unemployment rates varied significantly across different regions.
- Tripura recorded the highest average unemployment rate among the regions analyzed.
- The average unemployment rate was higher during the COVID period compared with the Pre-COVID period.
- The average estimated employment decreased during the COVID period.
- The labour participation rate also decreased during the COVID period.
- The analysis highlights a significant change in unemployment-related indicators during the COVID period.

## Visualizations

The project includes visualizations such as:

- Region-wise average unemployment rate
- Month-wise unemployment trends
- Time-series line charts
- Bar charts for regional unemployment rates
- Correlation heatmap
- Pre-COVID vs COVID-period comparison chart

## Conclusion

This project demonstrates how Python-based exploratory data analysis can be used to study unemployment trends in India.

The analysis examined regional differences, temporal patterns, and changes in unemployment-related indicators during the COVID period.

The comparison between the Pre-COVID and COVID periods showed that the average unemployment rate increased from approximately 9.51% to 17.77%. Meanwhile, estimated employment and labour participation rates decreased during the COVID period.

Overall, the project provides an analytical view of unemployment trends and demonstrates the use of Python, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

## Files

- `HajiraSafwan_Task2.ipynb` — Google Colab/Jupyter Notebook containing the complete analysis and visualizations.
- `README.md` — Project documentation.
