# Risk-Assessment-of-Loan-Default-A-Data-Science-Approach
Analyzing SBA loan data to predict default risk using machine learning and data analysis. Focused on real-world decision making, feature insights, and product thinking for better lending strategies.
# 📊 Loan Default Risk Analysis (SBA Dataset)

## 🚀 Overview

This project analyzes loan default risk using historical data from the U.S. Small Business Administration (SBA). The goal is to predict whether a loan will be **paid in full or defaulted**, helping financial institutions make better lending decisions.

This is not just a machine learning project — it focuses on **product thinking + data-driven decision making**.

---

## 🎯 Problem Statement

Banks face a critical question:

> “Should we approve this loan or not?”

Even with SBA guarantees, defaults can lead to losses.
This project builds models to **predict loan risk** and identify **key factors influencing repayment behavior**.

---

## 📁 Dataset

* Source: SBA Loan Dataset (Public)
* Records: 899,164+
* Features: 27 variables

Key variables include:

* Loan amount (DisbursementGross)
* Industry type (NAICS)
* Loan term
* Business type (new/existing)
* Real estate backing
* Loan status (Target variable)

---

## 🧠 Approach

### 1. Data Cleaning

* Handled missing values
* Converted categorical variables into usable formats
* Cleaned financial columns

### 2. Feature Engineering

* Created binary target variable:

  * 1 → Paid in Full (PIF)
  * 0 → Charged Off (Default)
* Derived features like:

  * Real estate-backed loans
  * Loan tenure insights

### 3. Exploratory Data Analysis (EDA)

Key insights:

* Loans backed by real estate have **lower default rates**
* Certain industries (Healthcare, Agriculture) show **better repayment behavior**
* Financial crisis periods (2008) show **higher default spikes**

---

## 📊 Models Used

* Logistic Regression
* Random Forest Classifier
* XGBoost
* PCA-based variants

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve

---

## 🏆 Key Insights

* Real estate-backed loans are significantly safer
* Industry type strongly impacts repayment probability
* Economic cycles influence default rates
* Feature importance highlights financial variables as key predictors

---

## 💡 Product Thinking Layer (What I Learned)

Instead of just building models, I asked:

* Where do risky loans come from?
* What features should banks prioritize?
* How can this improve decision-making?

### Example Decisions:

* Prioritize loans with collateral
* Adjust risk scoring based on industry
* Add stricter checks during economic downturns

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost

---

## 📌 Future Improvements

* Deploy as a web app (Streamlit)
* Real-time risk scoring dashboard
* More advanced feature engineering
* Model explainability (SHAP values)

---

## 📢 Why This Project Matters

This project demonstrates:

* Data analysis skills
* Product thinking
* Business understanding
* Ability to turn data into decisions

---

## 🤝 Let's Connect

If you're interested in:

* Data analysis
* Product thinking
* AI in decision-making

Feel free to connect or collaborate!
