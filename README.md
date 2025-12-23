# ✈️ Airline Customer Satisfaction Prediction using Decision Tree

## 📌 Project Overview
This project aims to analyze and predict airline customer satisfaction using a Decision Tree classification model. The objective is to understand key factors that influence passenger satisfaction and build a machine learning model capable of accurately classifying customers as satisfied or neutral/dissatisfied.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing on airline customer data
- Conduct exploratory data analysis (EDA) to identify trends and patterns
- Apply feature engineering techniques for model readiness
- Train and evaluate a Decision Tree classification model
- Assess model performance using standard evaluation metrics

---

## 🗂️ Dataset Description
The dataset contains passenger and service-related information, including:

- Gender
- Age
- Customer Type
- Type of Travel
- Class
- Flight Distance
- Service ratings such as Food and Drink, Check-in Service, and others
- Target variable: **Satisfaction** (Satisfied / Neutral or Dissatisfied)

---

## 🧹 Data Preprocessing & Exploratory Data Analysis
The following steps were performed:

- Loaded the dataset and performed initial inspection
- Removed unnecessary and duplicate columns
- Standardized column names for consistency
- Converted categorical target labels into numerical format
- Handled missing values
- Performed statistical analysis:
  - Mean satisfaction by gender
  - Mean satisfaction by age
  - Mean satisfaction by food and drink ratings
- Created visualizations to understand:
  - Overall satisfaction distribution
  - Relationship between flight distance and satisfaction
  - Impact of check-in service on customer satisfaction

---

## 🤖 Machine Learning Model
### Model Used
- **Decision Tree Classifier**

### Feature Engineering
- Encoded categorical variables such as gender, customer type, travel type, and class
- Scaled numerical features
- Split the dataset into training and testing sets

---

## 📊 Model Evaluation
The model was evaluated using the following metrics:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix
- Classification Report

These metrics provide insights into the model’s predictive performance and class-wise accuracy.

---

## 🧠 Key Insights
- Service-related features play a crucial role in determining customer satisfaction
- Proper data preprocessing significantly improves model accuracy
- Decision Trees offer clear interpretability, making them suitable for business analysis

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
