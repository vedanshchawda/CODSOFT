# Sales Prediction using Linear Regression

This project aims to predict sales using a linear regression model. It involves several steps including data preprocessing, visualization, model building, and evaluation. Let's break down each step.

## Importing Libraries

We start by importing the necessary libraries for data manipulation, visualization, and machine learning:

- `pandas` for data handling
- `numpy` for numerical operations
- `matplotlib.pyplot` for plotting graphs
- `seaborn` for enhanced data visualization
- `LinearRegression` and `train_test_split` from `scikit-learn` for creating and evaluating the model

## Gathering and Preprocessing Data

We load the sales data from a CSV file and inspect its structure and basic statistics. This step also involves checking for any missing values in the dataset.

## Data Visualization

We use histograms to visualize the distribution of the individual features (TV, Radio, Newspaper) and a pairplot along with a heatmap to visualize relationships between features and their correlations.

## Splitting Data for Training

The dataset is split into two parts: one for training the model and the other for testing its performance. This split is typically done to assess how well the model generalizes to new, unseen data.

## Model Building

We create a linear regression model, fit it to the training data (features vs. sales), and then predict sales using the testing data.

## Model Evaluation

We evaluate the model's performance by calculating the coefficient of determination (R-squared) score, which measures how well the model's predictions match the actual values. A higher R-squared value indicates a better fit.

## Model Details

We display the intercept and coefficients of the linear regression model. The intercept represents the expected sales value when all features are zero, while the coefficients indicate how much each feature contributes to the sales prediction.

In summary, this project demonstrates the process of building a sales prediction model using linear regression. It involves importing libraries, preprocessing data, visualizing relationships, creating and evaluating a predictive model, and interpreting the model's results.
