# Project: Churn Analysis for an Internet Service Provider

## Description
This project aims to analyze customer churn for an Internet Service Provider (ISP). The goal is to identify key factors that lead to customer churn and provide actionable insights to improve customer retention strategies.

## Objectives
- Analyze customer data to understand churn patterns.
- Use machine learning models to predict customer churn.
- Provide recommendations to reduce churn and improve customer retention.

## Data
The dataset contains simulated customer data, including:
- Demographics: Gender, Age.
- Account Information: Tenure, Service Type, Monthly Charges, Total Charges.
- Customer Feedback: Number of complaints.
- Churn Label: Indicates whether a customer has churned or not.

## Methodology
1. **Data Preparation:** Load and preprocess customer data, encoding categorical variables and scaling numerical features.
2. **Exploratory Data Analysis:** Analyze data distribution, correlations, and patterns related to churn.
3. **Modeling:** Train a Random Forest model to predict churn.
4. **Evaluation:** Use metrics like accuracy, confusion matrix, and ROC curve to evaluate model performance.
5. **Visualization:** Generate visualizations for data distribution, model performance, and churn patterns.

## Results
The model achieved the following performance metrics:
- **Accuracy:** Measures the proportion of correct predictions.
- **Confusion Matrix:** Displays true vs. predicted churn.
- **ROC Curve:** Plots the true positive rate against the false positive rate.

## How to Run
1. Ensure all dependencies are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn fpdf nbformat
   ```
2. Run the main script to execute the project:
   ```bash
   python churn_analysis.py
   ```

## Recommendations
- Use a larger, real-world dataset to improve model performance and insights.
- Experiment with other machine learning models, such as Logistic Regression or Gradient Boosting.
- Include additional features, like customer location or service usage patterns, for better predictions.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- fpdf
- nbformat

