# telco-customer-churn-analysis
Telco Customer Churn Analysis using Python, Pandas, Excel and Exploratory Data Analysis.
# 📊 Telco Customer Churn Analysis

## 📌 Project Overview

This project analyzes customer churn data from a telecommunications company to identify factors associated with customer churn and provide actionable recommendations for improving customer retention.

The project was completed as part of a **Data Analytics Internship at AnalystLab Africa**.

---

## 🎯 Business Problem

Customer churn can negatively affect a telecommunications company's recurring revenue and increase the cost of acquiring new customers.

The purpose of this project is to analyze customer data and identify customer groups that are more likely to leave the company.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Understand the overall customer churn rate.
* Identify customer segments with higher churn rates.
* Analyze the relationship between churn and contract type.
* Analyze the relationship between churn and customer tenure.
* Examine the relationship between charges and churn.
* Identify important customer retention opportunities.
* Provide actionable recommendations for management.

---

## 📂 Dataset

The dataset contains **7,043 customer records and 21 variables** before cleaning.

The dataset includes information about:

* Customer demographics
* Customer tenure
* Phone and internet services
* Additional services
* Contract type
* Payment method
* Monthly charges
* Total charges
* Customer churn

After cleaning, the dataset contained **7,032 records and 21 variables**.

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

1. Inspected the dataset structure and dimensions.
2. Checked data types.
3. Checked for missing values.
4. Identified blank values in the `TotalCharges` column.
5. Converted `TotalCharges` from object/text to numeric.
6. Removed 11 records with missing/invalid `TotalCharges`.
7. Checked for duplicate records.
8. Confirmed that the cleaned dataset contained 7,032 records.

No duplicate records were identified in the cleaned dataset.

---

## 🔍 Exploratory Data Analysis

The analysis examined customer churn based on several factors, including:

* Contract type
* Customer tenure
* Monthly charges
* Total charges
* Customer services
* Payment methods
* Customer demographics

---

## 📈 Key Findings

### Contract Type

Contract type showed a strong relationship with customer churn.

| Contract Type  | Churn Rate |
| -------------- | ---------: |
| Month-to-month |      42.7% |
| One year       |      11.3% |
| Two year       |       2.8% |

Month-to-month customers had the highest churn rate, while two-year contract customers had the lowest.

### Customer Tenure

Customers in their first year represented an important retention risk.

The **0–12 month tenure group had approximately 47.7% churn**.

This suggests that the early customer lifecycle is an important period for retention efforts.

### Overall Churn

In the original dataset:

* **5,174 customers stayed**
* **1,869 customers churned**
* Overall churn rate: approximately **26.6%**

---

## 💡 Recommendations

Based on the analysis, the following actions are recommended:

1. **Target month-to-month customers** with personalized retention offers.
2. **Improve customer onboarding** during the first 12 months.
3. **Encourage longer-term contracts** through suitable incentives.
4. **Monitor high-risk customers** using a churn dashboard.
5. **Review service bundles and pricing** for customers with higher charges.
6. Use customer data to develop **proactive retention campaigns**.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Excel**
* **GitHub**

---

## 📁 Project Files

The repository contains:

* `Telco_Customer_Churn_Analysis.ipynb` — Python analysis and EDA.
* `telco_customer_churn_cleaned.xlsx` — cleaned dataset.
* `Business_Understanding_Report.pdf` — business understanding report.
* `Dataset_Inspection_Report.pdf` — dataset inspection and cleaning report.
* `Telco_Customer_Churn_Presentation.pptx` — project presentation.

---

## 👩‍💻 Project Author

**Ilha**

Data Analytics Intern — AnalystLab Africa

---

## 📌 Conclusion

The analysis shows that customer churn is particularly high among **month-to-month customers and customers with shorter tenure**.

Focusing on early customer engagement, encouraging longer-term contracts, and implementing proactive retention strategies can help reduce churn and improve customer retention.

