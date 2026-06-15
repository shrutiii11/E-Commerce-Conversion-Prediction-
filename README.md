# Customer Conversion Prediction using Logistic Regression

## Project Overview

This project focuses on predicting whether a customer will convert based on demographic information and website interaction behavior. The objective is to build a robust machine learning pipeline that can identify potential customers and support data-driven marketing decisions.

## Problem Statement

Businesses invest significant resources in attracting website visitors, but not every visitor becomes a customer. Predicting conversion likelihood helps organizations target high-potential leads, optimize marketing campaigns, and improve conversion rates.

## Dataset

The dataset contains:

* Customer demographic information
* Website interaction and engagement metrics
* Conversion status (Target Variable)

## Project Workflow

### 1. Data Understanding & Exploration

* Examined dataset structure
* Performed exploratory data analysis (EDA)
* Identified missing values and outliers
* Analyzed feature distributions and relationships

### 2. Data Preprocessing

* Handled missing values
* Treated outliers where necessary
* Encoded categorical variables
* Scaled numerical features
* Built a reusable preprocessing pipeline

### 3. Feature Engineering

* Created meaningful features from existing variables
* Improved model interpretability and predictive power

### 4. Model Development

* Implemented Logistic Regression for binary classification
* Integrated preprocessing and modeling into a single pipeline
* Trained the model on training data

### 5. Model Evaluation

* Evaluated performance using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * ROC-AUC Score
* Analyzed confusion matrix
* Optimized classification threshold using F1-score

### 6. Prediction

* Generated predictions on unseen test data
* Prepared outputs for submission and deployment scenarios

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Key Learnings

Through this project, I gained practical experience in:

* End-to-end machine learning workflows
* Data cleaning and preprocessing
* Feature engineering techniques
* Logistic Regression modeling
* Classification metrics and threshold tuning
* Building scalable ML pipelines
* Model evaluation and performance optimization

## Project Structure

```text
├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   └── customer_conversion_prediction.ipynb
├── outputs/
│   └── predictions.csv
├── README.md
```

## Results

The Logistic Regression model successfully identified customer conversion patterns and provided interpretable predictions. Threshold optimization using F1-score improved the balance between precision and recall, making the model more effective for business decision-making.

## Future Improvements

* Hyperparameter tuning with GridSearchCV
* Testing advanced models (Random Forest, XGBoost, LightGBM)
* Feature selection techniques
* Model deployment using Flask or Streamlit
* Automated ML pipeline integration

## Author

**Shruti Sinha**

Aspiring Data Scientist passionate about Machine Learning, Analytics, and solving real-world business problems through data.
