# SpendDNA-MinorProject02
# 💳 SpendDNA — Personal Spending Analysis

**Unlox Internship | Week 2 Minor Project | Data Analytics**

## 📌 Project Overview

SpendDNA is a Python-based personal spending analysis project that transforms raw transaction records into structured financial insights. It analyzes income, expenses, spending categories, vendor activity, monthly trends, transaction timings, and unusual spending patterns.

The project focuses on data cleaning, transaction classification, exploratory data analysis (EDA), and rule-based spending behavior detection using Python.

## 🎯 Project Objectives

* Clean and standardize raw transaction data.
* Identify vendors from transaction descriptions.
* Categorize transactions into meaningful spending groups.
* Calculate income, expenses, net change, and savings rate.
* Analyze monthly and time-of-day spending patterns.
* Detect unusually large transactions using z-scores.
* Identify spending archetypes using predefined rules.
* Generate a final report with data-driven insights.

## 🛠️ Technologies Used

* **Python** — Core programming and analysis
* **Pandas** — Data cleaning, transformation, and analysis
* **NumPy** — Numerical operations and data handling
* **Google Colab / Jupyter Notebook** — Development environment

## 🔍 Key Features

### 1. Transaction Parser

* Removes duplicate records.
* Converts dates and transaction amounts into standard formats.
* Normalizes debit and credit transaction types.
* Handles invalid or missing values.

### 2. Vendor Extraction

Identifies vendors using keyword-based matching, including food delivery, e-commerce, transportation, subscriptions, utilities, and other transaction sources.

### 3. Spending Category Classification

Groups transactions into categories such as:

* Food Delivery
* Groceries
* E-commerce
* Transport
* Restaurants and Cafes
* Subscriptions
* Utilities
* Investments
* Fuel and Entertainment
* Housing and Personal Transfers

### 4. Spending Overview

Calculates:

* Total credits and debits
* Net financial change
* Savings rate
* Total analyzed transactions
* Unique vendors
* Highest-spending categories and vendors

### 5. Monthly Trend Analysis

Analyzes category-wise spending across January to June and compares monthly expenditure to identify increases and decreases.

### 6. Time-of-Day Analysis

Examines transaction activity by hour and category, including late-night food delivery patterns and the busiest transaction hours.

### 7. Anomaly Detection

Uses category-based z-scores to flag transactions with a z-score greater than 2 for further review.

### 8. Spending Archetypes

Applies predefined rules to identify descriptive spending patterns, such as food-focused spending, e-commerce spending, investment activity, late-night ordering, and saving behavior.

### 9. Bonus Analysis

* Weekday versus weekend spending
* Day-of-week expenditure
* Vendor cleanup audit
* Final report and key insights

## 📂 Project Structure

```text
SpendDNA/
├── SpendDNA_MinorProject02.ipynb
├── rahul_transactions.csv
└── README.md
```

*Update the filenames above if your repository uses a different structure.*

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open `SpendDNA_MinorProject02.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the required transaction CSV file to the notebook environment.
4. Ensure the CSV filename matches the path specified in the code.
5. Run all cells from top to bottom.
6. Review the generated spending summaries, anomaly results, and final insights.

## 📊 Expected Outcomes

The notebook produces:

* A cleaned transaction dataset
* Standardized vendor names and spending categories
* Financial summary metrics
* Monthly and hourly spending matrices
* Potential spending anomalies
* Rule-based spending archetypes
* A final report summarizing key findings

Actual results depend on the input transaction data and the execution of the notebook.

## 📚 Skills Gained

Through this project, I practiced:

* Python programming fundamentals
* Pandas data manipulation
* NumPy operations
* Data cleaning and preprocessing
* String processing and feature engineering
* Grouping, aggregation, and pivot tables
* Statistical anomaly detection
* Exploratory data analysis
* Writing data-driven summaries

## 🎓 Internship Learning

This Week 2 minor project strengthened my understanding of how raw financial transaction data can be processed and analyzed to uncover spending patterns and support data-driven decision-making.

## 🔐 Data Privacy

This project may involve financial transaction records. Only use authorized, appropriately anonymized sample data in public repositories. Never upload personal bank statements, account details, or other sensitive financial information to GitHub.

## 👨‍💻 Author

**Manvi**
Data Analytics Intern — Unlox
Week 2 Minor Project

---

*Disclaimer: SpendDNA is an educational data analytics project. Its spending labels and anomaly flags are descriptive and should not be treated as financial advice or definitive evidence of fraudulent transactions.*
