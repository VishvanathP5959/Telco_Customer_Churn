# Telco_Customer_Churn
# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a telecom service provider. The project uses customer demographic information, service subscriptions, contract details, tenure, and billing information to identify customers who may be at risk of leaving.

The main objective is to analyze customer data, build classification models, evaluate their performance, and generate predictions for new customer records. This project demonstrates how machine learning can support customer retention strategies and data-driven business decisions.

## 🎯 Project Objectives

- Analyze customer data to understand churn patterns.
- Clean and preprocess the dataset for machine learning.
- Handle missing or inconsistent values and encode categorical variables.
- Address class imbalance using SMOTE.
- Train and compare multiple machine learning classification models.
- Evaluate model performance using appropriate classification metrics.
- Save the trained model and encoders for future predictions.

## 🛠️ Technologies Used

- **Python** — Programming and model development
- **Pandas** — Data manipulation and preprocessing
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Exploratory data analysis and charts
- **Scikit-learn** — Data preprocessing, model training, cross-validation, and evaluation
- **Imbalanced-learn (SMOTE)** — Handling imbalanced target classes
- **XGBoost** — Gradient-boosting-based classification
- **Pickle** — Saving and loading trained model artifacts
- **Jupyter Notebook** — Interactive development and analysis

## 📂 Dataset

The project uses the **Telco Customer Churn dataset**, commonly distributed as `WA_Fn-UseC_-Telco-Customer-Churn.csv`.

The dataset contains customer information such as:

- Customer demographics
- Tenure and service subscriptions
- Internet and phone services
- Contract and payment methods
- Monthly charges and total charges
- Churn status (Yes/No)

The `Churn` column is the target variable used to train the classification models.

## ⚙️ Project Workflow

1. **Data Loading:** Import the customer churn dataset into a Pandas DataFrame.
2. **Data Exploration:** Inspect dataset dimensions, column types, unique values, and customer churn distribution.
3. **Data Cleaning:** Remove the customer ID column and handle inconsistent values in the total charges field.
4. **Data Preprocessing:** Convert categorical variables into numerical representations using Label Encoding.
5. **Train-Test Split:** Separate the input features and target variable into training and testing datasets.
6. **Class Imbalance Handling:** Apply SMOTE to the training data to improve the representation of the minority class.
7. **Model Training:** Train Decision Tree, Random Forest, and XGBoost classification models.
8. **Model Validation:** Use five-fold cross-validation to assess model performance.
9. **Model Evaluation:** Evaluate predictions using accuracy, confusion matrix, precision, recall, and F1-score.
10. **Model Saving and Prediction:** Save the model and feature names using Pickle, save the encoders, and prepare new customer records for prediction.

## 🤖 Machine Learning Algorithms

- **Decision Tree Classifier:** Learns decision rules from customer data.
- **Random Forest Classifier:** Combines multiple decision trees to improve predictive performance.
- **XGBoost Classifier:** Uses boosting to build a strong classification model.

The models can be compared using cross-validation results and test-set evaluation metrics to understand their relative performance.

## 📊 Evaluation Metrics

- **Accuracy:** Measures the overall proportion of correct predictions.
- **Precision:** Measures how many predicted churn cases are actually churn cases.
- **Recall:** Measures how many actual churn cases the model identifies.
- **F1-Score:** Balances precision and recall.
- **Confusion Matrix:** Shows correct and incorrect predictions for each class.
- **Cross-Validation Accuracy:** Assesses model performance across multiple training and validation folds.

## 💾 Model Persistence

The project uses Pickle to save and load the trained model and categorical encoders. This allows the preprocessing and prediction workflow to be reused for new customer records without retraining the model every time.

## 💼 Business Applications

- Identify customers who may be likely to leave a telecom provider.
- Support targeted customer retention campaigns.
- Help businesses investigate churn patterns and customer behavior.
- Assist customer relationship management teams in prioritizing retention efforts.
- Support data-driven decisions aimed at improving customer retention.

## 🚀 Future Improvements

- Tune hyperparameters to improve model performance.
- Compare additional algorithms and evaluation metrics.
- Analyze feature importance and explain individual predictions.
- Build an interactive prediction interface using Streamlit.
- Deploy the model through a web application or API.
- Monitor model performance as new customer data becomes available.

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer Churn Prediction using ML.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── customer_churn_model.pkl
├── encoders.pkl
├── requirements.txt
└── README.md
```

*Note: The CSV file and saved model artifacts should be included only if you have them available and are permitted to share them.*

## 👨‍💻 Author

**Vishvanath Panchal**

Aspiring Data Analyst | Machine Learning Enthusiast

Skills: Python, Pandas, NumPy, SQL, Machine Learning, Data Visualization, and Exploratory Data Analysis.
