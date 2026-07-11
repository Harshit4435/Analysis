# ☕ Cafe Sales Analysis

A complete **Data Cleaning** and **Exploratory Data Analysis (EDA)** project on a real-world messy cafe point-of-sale dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** in **Google Colab**.

---

## 📌 Project Overview

This project demonstrates the complete data analysis workflow—from cleaning messy transaction data to extracting actionable business insights through visualization.

The dataset contains missing values, placeholder errors (`ERROR`, `UNKNOWN`), inconsistent data types, and duplicate records, making it an ideal real-world data cleaning exercise.

### 🎯 Objectives

- Clean and preprocess raw transaction data
- Handle missing and inconsistent values
- Perform exploratory data analysis (EDA)
- Visualize business trends
- Generate insights and recommendations

---

## 📂 Repository Structure

```text
Analysis/
├── Data/
│   ├── dirty_cafe_sales.csv
│   └── cleaned_cafe_sales.csv
├── Notebook/
│   └── cafe_sales_analysis.ipynb
├── images/
└── README.md
```

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Replaced `ERROR` and `UNKNOWN` with `NaN`
- Converted numerical columns to correct data types
- Converted transaction dates to datetime format
- Reconstructed missing values using:

```
Total Spent = Quantity × Price Per Unit
```

- Recovered missing item names using price mapping
- Filled missing categorical values with `"Unknown"`
- Removed duplicate and invalid records

---

## 📊 Exploratory Data Analysis

The notebook includes analysis of:

- Revenue by product
- Revenue by payment method
- Revenue by location
- Monthly sales trend
- Month-over-month growth
- Weekday vs Weekend sales
- Day-of-week analysis
- Correlation analysis
- Outlier detection (IQR)
- Average Order Value (AOV)
- Top-selling items
- Payment method trends

---

## 📈 Visualizations

The project contains multiple visualizations including:

- Bar Charts
- Line Charts
- Heatmaps
- Box Plots
- Correlation Matrix
- Monthly Trend Graphs

---

## 💡 Key Insights

Example findings include:

- Certain menu items generate significantly higher revenue than others.
- Digital payment methods dominate customer transactions.
- Sales increase during weekends compared to weekdays.
- Monthly revenue follows a noticeable seasonal trend.
- A few high-value transactions were identified as outliers using the IQR method.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Harshit4435/Analysis.git
```

### Navigate into the project

```bash
cd Analysis
```

### Open the notebook

Launch Jupyter Notebook or upload the notebook to Google Colab.

Run all cells from top to bottom.

---

## 📁 Dataset

- **Raw Dataset:** `Data/dirty_cafe_sales.csv`
- **Cleaned Dataset:** `Data/cleaned_cafe_sales.csv`

---

## 👨‍💻 Author

**Harshit Thakur**

- GitHub: https://github.com/Harshit4435

---

⭐ If you found this project useful, consider giving the repository a **Star**.
