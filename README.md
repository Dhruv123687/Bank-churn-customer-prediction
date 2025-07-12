# Bank Customer Churn Prediction Project

This project predicts whether a bank customer will churn (leave the bank) based on customer profile information using machine learning techniques.

## ✅ Project Overview

- **Dataset Source:** Kaggle (Bank Customer Churn Prediction Dataset)  
  [Kaggle Dataset Link](https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset)
- **Algorithm Used:** Random Forest Classifier
- **Tools & Libraries:**
  - Python (pandas, numpy, matplotlib, seaborn)
  - scikit-learn
  - kagglehub (for dataset download)
  - Google Colab (for running notebooks)

---

## ✅ Project Workflow

1. **Data Collection:**
   - Downloaded using `kagglehub` directly in Google Colab.

2. **Data Preprocessing:**
   - Dropped unnecessary columns: `RowNumber`, `CustomerId`, `Surname`.
   - Encoded categorical variables: `Gender`, `Geography`.

3. **Model Building:**
   - Split data into training and testing sets using `train_test_split`.
   - Trained a Random Forest Classifier.
   - Evaluated with accuracy score, confusion matrix, and classification report.

4. **Results Visualization:**
   - Plotted top 10 feature importances using matplotlib.

---

## ✅ How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Dhruv123687/bank-churn-prediction.git
