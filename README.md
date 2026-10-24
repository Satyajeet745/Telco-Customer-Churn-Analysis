# 📊 Telco Customer Churn Analysis

An Exploratory Data Analysis (EDA) project focused on understanding customer churn patterns, identifying customer segments with higher churn counts, and recommending strategies to improve customer retention.

## 📌 Project Overview

Customer churn occurs when customers discontinue a company's services. Understanding churn patterns helps businesses identify potential retention challenges and make data-driven decisions.

In this project, I analyzed the Telco Customer Churn dataset using Python, Pandas, Matplotlib, and Seaborn to explore customer demographics, subscribed services, contract types, and churn behavior.

## 🎯 Project Objectives

- Understand the distribution of customers who churned and those who stayed.
- Analyze churn patterns across customer demographics and subscribed services.
- Explore the relationship between contract types and customer churn.
- Identify customer segments that require further investigation.
- Recommend strategies to improve customer retention.

## 🛠️ Tools and Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive analysis

## 📂 Project Structure

```text
Telco_Customer_Churn_Analysis/
│
├── Customer_Churn_Analysis.ipynb
├── Customer Churn.csv
├── Telco_Customer_Churn_Report.pdf
└── README.md
```

## 📁 Dataset

The project uses the Telco Customer Churn dataset, which contains customer information, subscribed services, account details, contract types, and churn status.

Important columns include:

- `gender` — Customer gender
- `SeniorCitizen` — Indicates whether the customer is a senior citizen
- `Partner` — Whether the customer has a partner
- `Dependents` — Whether the customer has dependents
- `InternetService` — Type of internet service
- `OnlineSecurity` — Online security subscription
- `TechSupport` — Technical support subscription
- `Contract` — Customer contract type
- `MonthlyCharges` — Monthly service charges
- `TotalCharges` — Total charges
- `Churn` — Whether the customer left the service

## 🔄 Project Workflow

**1. Data Loading**
- Loaded the dataset using Pandas.
- Examined the dataset's structure, dimensions, and column names.

**2. Data Cleaning**
- Inspected data types and missing values.
- Converted `TotalCharges` to a numeric data type where required.
- Prepared the dataset for exploratory analysis.

**3. Exploratory Data Analysis**
- Analyzed the overall distribution of churn.
- Compared churn counts across demographic groups.
- Explored churn patterns across internet and additional services.
- Examined contract types and customer service subscriptions.

**4. Data Visualization**
- Created count plots to compare churn categories.
- Used multiple subplots to analyze several customer attributes efficiently.
- Added chart titles, labels, and legends for readability.

**5. Insights and Recommendations**
- Summarized observed churn patterns.
- Identified customer segments for further investigation.
- Suggested customer retention strategies.

## 🔍 Key Insights

- Customers without partners and dependents show higher churn counts in the analyzed plots.
- Customers with phone service contribute a higher churn count.
- Fiber optic customers show a higher churn count than customers using DSL or no internet service.
- Customers without online security, online backup, device protection, and technical support show higher churn counts.
- Month-to-month contracts are an important area to investigate because they are commonly associated with higher churn than longer-term contracts in this dataset.

**Note:** Customer counts and churn rates are different measures. A higher churn count does not necessarily mean a group has a higher probability of churning. Segment-wise churn rates should be calculated to validate these patterns.

## 💡 Business Recommendations

- **Improve customer retention:** Identify customers who may be at risk of leaving and provide suitable retention offers.
- **Review pricing:** Evaluate whether monthly charges and service bundles provide sufficient value.
- **Encourage long-term contracts:** Offer transparent pricing and appropriate benefits for longer-term subscriptions.
- **Improve service quality:** Investigate internet reliability, technical issues, and customer complaints.
- **Promote additional services:** Explain the benefits of online security, backup, device protection, and technical support.
- **Monitor churn rates:** Track churn percentages by customer segment to measure retention performance.

## ▶️ How to Run the Project

**Prerequisites:** Python and Jupyter Notebook.

**1. Clone the repository**

```bash
git clone https://github.com/Satyajeet745/Telco-Customer-Churn-Analysis.git
```

**2. Navigate to the project folder**

```bash
cd Telco-Customer-Churn-Analysis
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open `Customer_Churn_Analysis.ipynb`** and run the cells in order. Ensure that `Customer Churn.csv` is in the same folder as the notebook.

## 📄 Project Report

The repository also includes `Telco_Customer_Churn_Report.pdf`, which provides a report for reviewing the project.



## 🏁 Conclusion

This project demonstrates how exploratory data analysis can help uncover customer churn patterns and support business decision-making. The findings provide a starting point for targeted retention strategies, while further analysis of churn rates and customer behavior can help validate the strongest risk factors.

## 👨‍💻 Author

**Satyajeet Kahandal**

- GitHub: [@Satyajeet745](https://github.com/Satyajeet745)

---

*If you find this project useful, feel free to explore the notebook and share feedback.*
