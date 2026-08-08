# Task 1: Iris Flower Classification

## Internship Program
AICTE Oasis Infobyte Internship Program

## Track
Data Science

## Objective

The objective of this project is to develop a machine learning classification model that identifies the species of an iris flower based on its physical measurements.

The three iris flower species considered in this project are:

- Setosa
- Versicolor
- Virginica

## Dataset

The Iris dataset was loaded directly from the scikit-learn library using the built-in `load_iris()` dataset.

The dataset contains 150 records and 5 original columns, including four flower measurement features and the target variable.

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target

The target variable represents the iris flower species.

A species column was also added to make the classification results easier to interpret.

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

The project followed these steps:

1. Loaded the Iris dataset using scikit-learn.
2. Inspected the number of rows and columns.
3. Examined the column names and data types.
4. Performed descriptive statistical analysis.
5. Checked for missing values.
6. Added species names to the dataset.
7. Performed exploratory data analysis.
8. Created visualizations to understand feature distributions and relationships.
9. Discussed feature selection and identified the most discriminative features.
10. Split the dataset into training and testing sets.
11. Trained two different classification models.
12. Evaluated the models using accuracy, precision, recall, and F1-score.
13. Compared the model performances.
14. Identified the best-performing classification model.

## Machine Learning Models

The following classification models were trained:

1. Logistic Regression
2. Random Forest Classifier

## Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.966667 | 0.969697 | 0.966667 | 0.966583 |
| Random Forest | 0.900000 | 0.902357 | 0.900000 | 0.899749 |

## Best-Performing Model

Logistic Regression was identified as the best-performing model based on the evaluation results.

It achieved:

- Accuracy: 0.966667
- Precision: 0.969697
- Recall: 0.966667
- F1-Score: 0.966583

The Logistic Regression model achieved better overall performance than the Random Forest model on the test dataset based on the reported evaluation metrics.

## Feature Selection

The project includes an analysis of the iris flower features to understand which measurements are most useful for distinguishing between the three species.

The petal-related measurements show strong differences between iris species and are useful features for classification.

## Conclusion

This project demonstrates the use of machine learning classification techniques to identify iris flower species based on physical measurements.

Two classification models, Logistic Regression and Random Forest, were trained and evaluated. Logistic Regression achieved the best overall performance among the tested models, with an accuracy of 0.966667 and an F1-Score of 0.966583.

The project demonstrates the complete machine learning workflow, including data loading, exploratory data analysis, visualization, feature analysis, model training, evaluation, and model comparison.

## Files

- `HajiraSafwan_Task1.ipynb` — Google Colab/Jupyter Notebook containing the complete analysis and machine learning implementation.
- `README.md` — Project documentation.
