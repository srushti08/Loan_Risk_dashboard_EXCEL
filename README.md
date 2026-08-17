# Loan Risk Dashboard – Excel

An Excel-based Loan Risk Analysis and Dashboard project built to analyze loan applications, approval patterns, and applicant risk levels.

## 📌 Project Overview

The goal of this project is to transform raw loan application data into meaningful insights using Microsoft Excel.

The project covers the complete workflow:

**Raw Data → Data Cleaning → Data Transformation → Pivot Table Analysis → Dashboard → Insights**

## 🎯 Business Questions

This dashboard helps answer questions such as:

- How many loan applications were received?
- What percentage of applications were approved?
- How many applications were rejected?
- Which risk category has the most applicants?
- How does income level relate to loan approval?
- What is the loan-to-income ratio of applicants?
- How do approval patterns vary across applicant groups?

## 🛠️ Tools & Skills Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Pivot Charts
- Slicers
- Excel Formulas
- Data Cleaning
- Data Transformation
- Data Analysis
- Dashboard Development

## 🧹 Data Cleaning & Transformation

The raw dataset was cleaned using Power Query.

Steps included:

- Removed duplicate records
- Identified and handled missing values
- Corrected data types
- Replaced missing income values using the median income
- Removed records with missing critical fields
- Created an **Income Group** column
- Created a **Risk Category** column
- Created a **Loan-to-Income Ratio** column

## 📊 Analysis

Pivot Tables were created to analyze:

- Loan approval vs rejection
- Risk category distribution
- Income group vs loan status
- Gender-based application analysis
- Average credit score by risk category
- Average loan amount by gender and loan status

## 📈 Dashboard

The final dashboard contains:

- Total Applications
- Approved Loans
- Rejected Loans
- Approval Rate
- Loan Status Distribution
- Risk Category Distribution
- Interactive Gender Slicer

## 🔍 Key Insights

From the analysis:

- **813** loan applications remained after data cleaning.
- **228 applications were approved**, while **585 were rejected**.
- The overall approval rate was approximately **28.04%**.
- **High Risk** applicants represented the largest risk category.
- Low-income applicants had a substantially lower approval rate compared with medium- and high-income groups.
- Loan-to-income ratio was used as an additional indicator for evaluating applicant risk.

## 📁 Project Structure

```text
Loan_Risk_dashboard_EXCEL/
│
├── Dataset/
│   └── loan_approval_data.csv
│
├── Loan_Risk_Dashboard.xlsx
│
└── README.md
