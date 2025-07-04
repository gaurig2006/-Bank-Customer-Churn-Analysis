# 📊 Bank Customer Churn Analysis

## 🔍 Project Overview

This project analyzes customer churn behavior in a bank using structured data and applies exploratory data analysis (EDA) and classification modeling to understand and predict customer retention. The objective is to derive actionable insights from patterns and predict the likelihood of a customer leaving the bank.

---

## 📁 Files

| File | Description |
|------|-------------|
| `BankCustomerChurn.ipynb` | Main notebook containing EDA, preprocessing, and classification models. |
| `churn.csv` | The dataset containing bank customer details and churn labels. |

---

## 🧠 Features Used

The dataset includes:
- **Demographics**: Gender, Geography, Age
- **Banking behavior**: Balance, Credit Score, Tenure
- **Account info**: Number of products, Has Credit Card, Is Active Member
- **Outcome variable**: `Exited` (1 = churned, 0 = retained)

---

## 🔧 Steps Covered in Notebook

1. **Data Cleaning & Preprocessing**
   - Handling categorical variables using encoding
   - Checking for missing values and duplicates
2. **Exploratory Data Analysis (EDA)**
   - Distribution plots, churn rate by feature
   - Correlation heatmaps
3. **Feature Engineering**
   - Creation of new relevant features (e.g. age bins, activity levels)
4. **Modeling**
   - Trained models: Logistic Regression, Decision Tree, Random Forest, etc.
   - Evaluation using Accuracy, ROC-AUC, Confusion Matrix

---

## 📈 Key Findings

- **Age** and **Balance** strongly correlate with churn.
- Inactive members and customers with multiple products are more likely to churn.
- Geography and gender showed minor but notable trends.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning (classification models)

---

## 🎯 How to Run

1. Clone the repository
2. Make sure you have Python 3.7+ installed
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
