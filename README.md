# 📈 Regression Analysis Between US Factor Returns and the S&P Index

Welcome to my first data science project — a financial analysis of how various US equity factors correlate with the S&P index using regression modeling.

This project was completed as part of my Data Science course under the supervision of **Kourosh Sadeghi**.

## 🧠 Project Overview

In this notebook, we perform a **regression analysis** between monthly **US factor returns** and the **S&P index returns**. The goal is to understand the relationship and correlation between different financial factors and the overall market index.

---

## 🔍 Steps Overview

### 1. 📥 Data Collection
- Downloaded **monthly US factor return data** (153 factors) from [JKP Factors](https://www.jkfactors.com/).
- Retrieved **S&P index return data** from a separate Excel source.

### 2. 🧹 Data Cleaning & Preprocessing
- Merged the two datasets based on **year-month timestamps**.
- Handled inconsistencies in date formats (e.g., strings vs datetime objects).
- Managed missing values and ensured consistent formatting across columns.

### 3. 📊 Regression Analysis
- Selected a sample factor from the top 10 most frequently observed.
- Calculated the **correlation coefficient** between the factor and the S&P index.
- Performed **OLS (Ordinary Least Squares)** regression to examine the predictive relationship.

### 4. 📈 Data Visualization
To enhance the insights, we visualized the relationship between factor and index returns:
- 📉 **Line Plot** comparing index and factor returns over time.
- ⚫ **Scatter Plot** with regression line to illustrate linear relationships.
- 🔥 **Heatmap** showing correlation values between the top 10 factors and the index.

---

## 📌 Key Learnings

This project demonstrates:
- Practical skills in **data preprocessing** and **data integration**.
- Usage of **pandas**, **NumPy**, **matplotlib**, **seaborn**, and **statsmodels**.
- Fundamental understanding of **correlation**, **regression modeling**, and **data visualization** in finance.

---

## 🚀 How to Run

1. Clone the repository.
2. Update the file paths in the notebook with your local directories.
3. Run the Jupyter Notebook `cleaned_analysis.ipynb`.

---

## 📁 File Structure

```
📦 project/
 ┣ 📜 cleaned_analysis.ipynb
 ┣ 📜 README.md
 ┗ 📁 data/
     ┣ 📄 sp_index.xlsx
     ┗ 📄 [usa]_[all_factors]_[monthly]_[ew].csv
```

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out or open an issue!

---
