# Customer Churn Analysis and Prediction

## Project Overview

This project focuses on analyzing customer churn in a telecommunications company and developing a machine learning model to predict whether a customer is likely to leave the service.

## Dataset

* Dataset: Telco Customer Churn Dataset
* Records: 7043 customers
* Target Variable: Churn

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn

## Project Tasks

### Task 1: Data Preparation

* Loaded the dataset into Google Colab.
* Checked dataset structure and data types.
* Verified that there were no missing values.
* Converted the Churn column into numerical format.
* Removed the customerID column.
* Applied one-hot encoding to categorical features.

### Task 2: Train-Test Split

* Split the dataset into 80% training data and 20% testing data.
* Used stratified sampling to maintain class distribution.

### Task 3: Feature Selection

Selected important features affecting customer churn, including:

* Tenure
* Monthly Charges
* Contract Type
* Online Security
* Tech Support
* Internet Service Type
* Paperless Billing

### Task 4: Model Selection

* Selected Logistic Regression as the binary classification algorithm for churn prediction.

### Task 5: Model Training

* Trained the Logistic Regression model using the training dataset.
* Used customer attributes as input features and Churn as the target variable.

### Task 6: Model Evaluation

The model was evaluated using the testing dataset.

#### Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 78%   |
| Precision | 60%   |
| Recall    | 50%   |
| F1-Score  | 55%   |

Classification Report:

| Class         | Precision | Recall | F1-Score |
| ------------- | --------- | ------ | -------- |
| Non-Churn (0) | 0.83      | 0.88   | 0.85     |
| Churn (1)     | 0.60      | 0.50   | 0.55     |

## Conclusion

A Logistic Regression model was successfully developed to predict customer churn. The model achieved an accuracy of 78% on the test dataset and demonstrated the ability to identify customers at risk of churning. The project provides valuable insights that can help telecommunications companies improve customer retention strategies.

