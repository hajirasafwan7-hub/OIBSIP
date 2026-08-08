# Task 5: Sales Prediction Using Python

## Internship Program
AICTE Oasis Infobyte Internship Program

## Track
Data Science

## Objective

The objective of this project is to build a machine learning regression model that predicts product sales based on advertising expenditure across different media channels, including TV, Radio, and Newspaper.

## Dataset

The dataset contains 200 records and includes the following variables:

- TV: Advertising expenditure on TV
- Radio: Advertising expenditure on Radio
- Newspaper: Advertising expenditure on Newspaper
- Sales: Product sales

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

The project followed these steps:

1. Loaded the advertising and sales dataset.
2. Inspected the dataset structure and dimensions.
3. Removed the unnecessary index column.
4. Checked for missing values.
5. Performed descriptive statistical analysis.
6. Created a pairplot to explore relationships between variables.
7. Created scatter plots for:
   - Sales vs TV advertising
   - Sales vs Radio advertising
   - Sales vs Newspaper advertising
8. Created a correlation matrix heatmap.
9. Split the dataset into training and testing sets using an 80/20 split.
10. Trained a Linear Regression model.
11. Trained a Random Forest Regressor model.
12. Evaluated both models using MAE, RMSE, and R² Score.
13. Compared the performance of both models.
14. Analyzed feature importance using the Random Forest model.
15. Identified the most influential advertising channel.

## Model Performance

### Linear Regression

- MAE: 1.460757
- RMSE: 1.781600
- R² Score: 0.899438

### Random Forest Regressor

- MAE: 0.620100
- RMSE: 0.768591
- R² Score: 0.981284

## Best-Performing Model

The Random Forest Regressor was identified as the best-performing model.

It achieved:

- Lowest MAE: 0.620100
- Lowest RMSE: 0.768591
- Highest R² Score: 0.981284

The R² Score of 0.981284 indicates that the model explains approximately 98.13% of the variation in sales in the test dataset.

## Feature Importance

The feature importance analysis of the Random Forest model produced the following results:

| Feature | Importance |
|---|---:|
| TV | 0.624810 |
| Radio | 0.362201 |
| Newspaper | 0.012989 |

TV advertising had the highest feature importance, followed by Radio. Newspaper had the lowest feature importance among the three advertising channels.

## Conclusion

This project demonstrates how machine learning and exploratory data analysis can be used to understand the relationship between advertising expenditure and product sales.

Two regression models were trained and evaluated. The Random Forest Regressor performed better than Linear Regression based on MAE, RMSE, and R² Score.

The feature importance analysis showed that TV advertising was the most influential feature for predicting sales in this dataset, followed by Radio, while Newspaper had relatively low importance.

## Files

- `HajiraSafwan_Task5.ipynb` — Google Colab/Jupyter Notebook containing the complete analysis and machine learning implementation.
- `README.md` — Project documentation.
