# Telco Customer Churn Prediction

## Project Overview

This project explores customer churn prediction using machine learning techniques. The objective is to analyze customer data, identify patterns associated with churn, and evaluate classification models capable of predicting whether a customer is likely to leave a telecommunications company.

---

## Dataset

The dataset contains customer demographic information, service subscriptions, billing details, and churn status.

Target Variable:

* Churn

---

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns.
* Converted the TotalCharges column to numeric format.
* Handled missing values resulting from data conversion.
* Encoded the Churn column into numerical values.
* Applied one-hot encoding to categorical variables.
* Prepared the dataset for machine learning analysis.

---

## Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to better understand the dataset and feature relationships.

Visualizations created:

* Correlation Heatmap
* Tenure Distribution Histogram
* Monthly Charges vs Total Charges Scatter Plot
* Tenure Box Plot

The visualizations were used to explore data distributions and relationships between variables.

---

## Machine Learning Models

Two classification models were developed and evaluated:

### Logistic Regression

Used as a baseline classification model for predicting customer churn.

### Random Forest Classifier

Used to compare performance against Logistic Regression and evaluate an ensemble learning approach.

---

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Performance metrics were compared to assess the effectiveness of each model.

---

## Results

The project compared Logistic Regression and Random Forest models using classification metrics.

The analysis highlighted differences in model performance and demonstrated the importance of considering multiple evaluation metrics when assessing classification models.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Author
Veli Nhlapo

GitHub: https://github.com/AiVintage
LinkedIn: https://www.linkedin.com/in/veli-nhlapo-721351373
