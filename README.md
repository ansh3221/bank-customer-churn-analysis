# 🏦 Bank Customer Churn Analysis & Prediction

**Turning customer data into meaningful insights for better retention decisions.**

## 📌 Project Overview

Customer retention is an important challenge in the banking industry. Understanding why customers leave can help banks improve their services and build stronger customer relationships.

This project explores bank customer behavior through **data analysis, machine learning, and interactive Tableau dashboards** to identify churn patterns, predict potential customer churn, and highlight customers who may need additional attention.

## 🎯 Project Objectives

- Analyze customer demographics and banking behavior.
- Identify patterns associated with customer churn.
- Build and evaluate machine learning classification models.
- Generate customer churn predictions and risk categories.
- Visualize findings to support data-driven retention strategies.

## 🛠️ Technologies Used

- **Python** — Data analysis and machine learning
- **Pandas & NumPy** — Data manipulation
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Model building and evaluation
- **Jupyter Notebook** — Analysis and experimentation
- **Tableau** — Interactive dashboards
- **CSV** — Dataset and prediction outputs

## 📂 Project Structure

```text
Bank_Customer_Churn_Project/
├── data/
│   └── bank_churn.csv
├── notebooks/
│   └── bank_churn_analysis.ipynb
├── output/
│   ├── customer_predictions.csv
│   └── screenshots/
├── Tableau/
│   └── Bank_Cust_Churn.twb
└── README.md
```

## 📊 Tableau Dashboard Highlights

The project includes multiple dashboard views:

### 1. Bank Overview
- Total customers and total balance
- Average balance and credit score
- Customer churn rate
- Geographic distribution
- Active versus inactive customers

### 2. Customer Analysis
- Churn by gender and age group
- Credit score and balance analysis
- Churn patterns by tenure
- Number of banking products held by customers

### 3. Churn Prediction & Risk Analysis
- Predicted customer churn probabilities
- Customer risk categorization
- High-risk customer identification
- Customer-level analysis for potential retention actions

### 4. High-Risk Customer Analysis
- Detailed customer risk information
- Filters for geography, age, credit score, and membership status
- Identification of customers who may benefit from targeted retention efforts

## 🤖 Machine Learning Approach

The project explores three classification algorithms:

1. **Logistic Regression** — A baseline classification model.
2. **Decision Tree** — Identifies patterns through decision rules.
3. **Random Forest** — Combines multiple decision trees to improve predictive performance.

Model performance can be evaluated using accuracy, precision, recall, F1-score, and ROC-AUC, depending on the evaluation performed in the notebook.

## 🔍 Key Analytical Questions

- Which customer groups show higher churn?
- How does age relate to customer retention?
- What patterns appear across geography and credit score?
- How are balance, tenure, and product ownership associated with churn?
- Which customers are predicted to be at greater risk of leaving?

## 🚀 How to Explore the Project

1. Open `notebooks/bank_churn_analysis.ipynb` to review the analysis and model development.
2. Explore `data/bank_churn.csv` to understand the dataset.
3. Review `output/customer_predictions.csv` for the generated prediction results.
4. Open `Tableau/Bank_Cust_Churn.twb` in Tableau Desktop to explore the dashboards.

**Note:** The Tableau workbook may require the original dataset or a refreshed data connection to display correctly.

## 💡 Learning Outcomes

This project strengthened my practical understanding of data preprocessing, exploratory data analysis, machine learning, model evaluation, and dashboard development.

More importantly, it helped me understand how analytical insights can go beyond numbers to address real business challenges and support better customer experiences.

## 👨‍💻 Author

**Ansh Surve**  
BSc Data Science Student

GitHub: [@ansh3221](https://github.com/ansh3221)

---

*Developed as a Data Science project for educational and portfolio purposes. Predictions indicate potential churn risk and should not be treated as certainty.*
