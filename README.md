# Telecom-Customer-Churn-Analysis
# 📡 Telecom — Customer Churn Analysis

> *Transforming raw numbers into Retention stories*

---

## 📖 Overview

Exploratory Data Analysis of a Telecom Customer Churn dataset using Python. This project uncovers churn patterns and provides visual storytelling with insights from contract type, payment method, tenure, and service usage.

---

## 🎯 Objective

- Perform data cleaning and exploratory analysis on the Telecom Churn dataset.
- Visualize patterns and churn distributions using Python libraries.
- Identify key factors that influenced customer churn (contract, tenure, payment method, services).
- Build a foundation for predictive churn modeling.

---

## 💡 Key Insights

| Factor | Insight |
|---|---|
| 📋 **Contract Type** | Month-to-month customers churn far more than those on 1- or 2-year contracts. |
| ⏳ **Tenure** | Customers who leave mostly do so within the first 1–2 months of service. |
| 👴 **Senior Citizens** | A comparatively higher percentage of senior citizens churn. |
| 💳 **Payment Method** | Customers paying via electronic check have the highest churn rate. |
| 🔒 **Services** | Customers without OnlineSecurity, TechSupport, or OnlineBackup are more likely to churn. |
| 🚻 **Gender** | Churn rates are similar across genders — not a significant differentiator. |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3.8+** | Core programming language |
| **Pandas, NumPy** | Data manipulation and preprocessing |
| **Matplotlib, Seaborn** | Visualizations for storytelling |
| **Jupyter Notebook** | Interactive workflow for analysis |
| **CSV Dataset** | Input data file (`Customer Churn.csv`) |

---

## 📊 Visualizations

Generated charts include:

- 📌 Count & Percentage of Churned Customers
- 📌 Churn by Gender
- 📌 Senior Citizen vs Churn Rate
- 📌 Tenure Distribution: Churned vs Retained
- 📌 Churn by Contract Type
- 📌 Service Usage vs Churn (9 services)
- 📌 Churn by Payment Method

---

## 📁 Repository Structure

```
telecom-churn-analysis/
├── notebooks/
│   └── telecom_churn_analysis.ipynb   # Main analysis notebook
├── data/
│   └── README.md                      # Instructions to download the dataset
├── src/
│   └── utils.py                       # Reusable helper functions
├── reports/
│   └── summary.md                     # Key findings and recommendations
├── requirements.txt                   # Python dependencies
├── .gitignore                         # Git ignore rules
└── README.md                          # This file
```

---

## 🗂️ Dataset

The dataset is sourced from the [**Kaggle Telco Customer Churn**](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) competition.

Place the downloaded file at:

```
data/Customer Churn.csv
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/telecom-churn-analysis.git
cd telecom-churn-analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Add the Dataset

Download `WA_Fn-UseC_-Telco-Customer-Churn.csv` from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), rename it to `Customer Churn.csv`, and place it in the `data/` folder.

### 4. Run the Notebook

```bash
jupyter notebook notebooks/telecom_churn_analysis.ipynb
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
