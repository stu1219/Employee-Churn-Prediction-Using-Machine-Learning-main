# 🚀 Employee Churn Prediction

## Overview
This project uses machine learning to predict the likelihood of employees leaving a company. It employs a variety of models including Logistic Regression, Decision Tree, Random Forest, and XGBoost to evaluate their performance.

## 📊 Dataset
The dataset used, `HR_Dataset.csv`, consists of the following features:
- `satisfaction_level`: Employee satisfaction level (float)
- `last_evaluation`: Last evaluation score (float)
- `number_project`: Number of projects assigned (int)
- `average_monthly_hours`: Average monthly hours worked (int)
- `time_spend_company`: Time spent at the company (int)
- `Work_accident`: Whether there has been a work accident (1 or 0)
- `promotion_last_5years`: Whether there has been a promotion in the last five years (1 or 0)
- `departments`: Department name (categorical)
- `salary`: Salary category (low, medium, high)

## ⚙️ Setup
### Prerequisites
Ensure Python is installed along with these libraries:
- pandas
- numpy
- scikit-learn
- xgboost
- pickle

### Installation
To install the required libraries, run:
```bash
pip install pandas numpy scikit-learn xgboost
📝 Usage
Load the data from HR_Dataset.csv.
Execute the script to train the model and make predictions.
📊 Features
Numerical data is normalized.
Categorical data is encoded appropriately.
Models are evaluated based on accuracy, precision, and recall.
💾 Saving Models
Models are saved using pickle for persistence, allowing for future use without retraining.

🖥️ GUI Application
A Tkinter GUI is provided for:

Single Entry Prediction: Directly input data to predict employee churn.
Bulk Processing: Load and predict churn for multiple employees from a CSV file.
📈 Visualization (Optional)
Visualize predictions and model performance using matplotlib.

🧪 Model Comparison
A function is included to test and compare various machine learning classifiers on their performance.

sql
Copy code
This README file is crafted to be both comprehensive and user-friendly, guiding users smoothly through the setup, usage, and features of the project.
