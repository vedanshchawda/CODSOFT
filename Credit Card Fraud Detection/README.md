# Credit Card Fraud Detection with Undersampling and Logistic Regression



## Overview

This project is dedicated to building a credit card fraud detection model using undersampling and the logistic regression classification algorithm. Detecting fraudulent credit card transactions is crucial for financial security. Here, we'll guide you through the process of preparing and normalizing transaction data, addressing class imbalance through undersampling, and training a logistic regression model for classification.

## Dataset

The dataset used in this project contains credit card transactions, each labeled as fraudulent or genuine. It includes features like transaction amount, merchant, and time. Handling this data with utmost care and ensuring its privacy is essential.

## Preprocessing and Normalization

Our data preparation steps involve:

- **Data Cleaning:** We handle missing values, duplicate entries, and outliers to ensure data quality.
- **Feature Engineering:** Creating relevant features to potentially improve model performance.
- **Normalization:** Scaling features to have a consistent range, a crucial step for logistic regression.

## Addressing Class Imbalance

Class imbalance is a common issue in fraud detection, where genuine transactions far outnumber fraudulent ones. We tackle this imbalance using undersampling, where we randomly reduce the number of genuine transactions to balance the dataset.

## Logistic Regression Model

We choose logistic regression as our classification algorithm. Logistic regression is suitable for binary classification tasks and interpretable, making it a good choice for fraud detection.

## Evaluation Metrics

We evaluate the model's performance using metrics tailored for imbalanced datasets:

- **Precision:** The proportion of true positives among all predicted positives.
- **Recall:** The proportion of true positives among all actual positives.
- **F1-Score:** The harmonic mean of precision and recall, providing a balance between them.
- **Area Under the Receiver Operating Characteristic Curve (AUC-ROC):** Measures the model's ability to distinguish between classes.

## Model Improvement

To enhance the model's performance:

- **Hyperparameter Tuning:** We fine-tune logistic regression hyperparameters for optimal results.
- **Feature Selection:** Identifying and using the most relevant features.
- **Ensemble Methods:** Combining multiple models to potentially improve accuracy.

## Usage

1. Ensure you have the required dependencies installed, as listed in the `requirements.txt` file.
2. Preprocess the dataset using the `preprocess_data.py` script.
3. Implement undersampling to balance the class distribution.
4. Train and evaluate the logistic regression model using the `train_and_evaluate.py` script.
5. Experiment with hyperparameter tuning and feature selection for further improvement.

## Conclusion

This project showcases the development of a credit card fraud detection model using logistic regression and undersampling. The goal is to provide a reliable framework for identifying fraudulent transactions with high precision and recall, contributing to enhanced financial security.

Always handle the dataset with care, ensuring privacy and adherence to data protection regulations.

Happy fraud detection with undersampling and logistic regression!
