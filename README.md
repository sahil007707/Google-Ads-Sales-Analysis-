# 📈 Google Ads Sales Analysis

This project explores and analyzes sales data derived from Google Ads campaigns to identify patterns, evaluate ad effectiveness, and predict customer behavior. The analysis leverages both statistical visualization and machine learning techniques for actionable business insights.

---

## 📂 Project Structure

- `Google Ads Sales Analysis.ipynb` — Full notebook covering EDA, data cleaning, preprocessing, and predictive modeling.

---

## 🔍 Objective

- Understand how different ad strategies (targeting, time, cost, etc.) affect sales.
- Clean and preprocess inconsistent data, especially date fields.
- Predict customer purchase likelihood using logistic regression.

---

## 🧼 Data Cleaning

### Major Issues Resolved:
- Inconsistent date formats in `Ad_Date` field (e.g. `20-11-2024`, `2024/11/20`, etc.) were parsed and standardized.
- Removed or handled missing/null entries.
- Encoded categorical features using `LabelEncoder`.
- Applied `StandardScaler` to normalize numerical features.

---

## 📊 Exploratory Data Analysis

### Key Insights:
- Peak ad performance is observed on specific weekdays.
- Higher CTR and impressions do not always correlate with sales — suggesting optimization scope.
- Certain keywords and targeting parameters led to significantly better conversion rates.

> Libraries Used: `Pandas`, `Seaborn`, `Matplotlib`, `Plotly`

---

## 🤖 Predictive Modeling

A **Logistic Regression** model was implemented to classify whether a customer is likely to make a purchase based on ad-related features.

### Workflow:
- Feature selection & encoding
- Train-Test split using `train_test_split`
- Model fitting and evaluation (accuracy, precision, recall)

> ML Tools: `Scikit-learn`, `LabelEncoder`, `StandardScaler`, `LogisticRegression`

---

## 📌 Results

- Model achieved strong classification accuracy for identifying likely buyers.
- Logistic Regression provided baseline performance; future work could include:
  - Decision Trees, Random Forest, XGBoost
  - Cross-validation and Grid Search

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sahil007707/google-ads-sales-analysis.git
   cd google-ads-sales-analysis
