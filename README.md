# Cleaning the Titanic Dataset

This project focuses on cleaning the Titanic dataset from Kaggle, handling missing values, and preprocessing categorical variables.

## Dataset

The dataset used in this project is the `train.csv` file from the Titanic - Machine Learning from Disaster competition on Kaggle.

## Project Overview

The project consists of the following steps:

1.  **Data Loading and Exploration:** The dataset is loaded and explored.
2.  **Missing Value Handling:** Missing values in 'Age', 'Cabin', and 'Embarked' are handled.
3.  **Categorical Variable Conversion:** 'Sex' and 'Embarked' are converted to numerical representations.
4.  **Feature Reduction:** Unnecessary columns are dropped.
5.  **Visualization:** The cleaned data is visualized.

## Key Findings

* Missing age values were filled with the median age.
* The 'Cabin' column was dropped due to a high number of missing values.
* Categorical variables were converted to numerical representations.

## Libraries Used

* Pandas
* Seaborn
* Matplotlib
