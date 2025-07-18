# 📊 Census Income Lens — Predicting Income with Machine Learning

Welcome to **IncomeLens**, a hands-on machine learning project where I dive into real-world data to predict whether an individual's income exceeds $50,000 annually, based on census survey data. I built this project as part of my learning journey into classification algorithms and data preprocessing.

---

## 🧠 Problem Statement

**Can data tell us who might earn over $50K a year?**

Using the U.S. Census Income dataset, this project builds a classification pipeline to predict income brackets from demographic and economic features like age, education, marital status, capital gains, occupation, and more.

---

## 🌍 Why It Matters

Income inequality is a critical social and economic issue. By identifying key predictors of income:
- Policymakers can analyze factors contributing to economic disparity
- Organizations can audit for biases in hiring or lending practices
- Individuals can gain better insight into the socioeconomic landscape

This isn’t just about accuracy scores it’s about **stories behind data**, and making insights that influence fairness and inclusion.

---

## 📦 Dataset

The dataset contains **32,000+ rows** and **15 features**, including:

- `age`, `education`, `occupation`, `race`, `sex`, and `hours-per-week`
- Target variable: `annual_income` (<=50K or >50K)

Some missing values were marked as `"?"` and handled appropriately during cleaning.

---

## 🔍 Models Explored

To learn from the data and test various approaches, I trained three classification models:

- **🔹 Logistic Regression** — Fast, interpretable baseline
- **🌳 Decision Tree** — Splits data by rules like human decision-making
- **🌲 Random Forest** — Ensemble model with high accuracy and robustness

---

## 🧪 Project Workflow

1. **Import & Inspect Data**  
   Read the CSV, check for nulls or inconsistencies, understand feature data types.

2. **Data Cleaning**  
   - Handled missing values (e.g., replacing `"?"`)
   - Encoded categorical variables using `LabelEncoder`

3. **Feature Engineering & Splitting**  
   - Created X (features) and y (target)
   - Split into training / test sets with `train_test_split`

4. **Model Training & Evaluation**  
   - Trained each model with `sklearn`
   - Evaluated using **accuracy score** and comparison metrics
