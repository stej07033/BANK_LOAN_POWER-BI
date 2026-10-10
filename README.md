# 🏦 Bank Loan Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **Bank Loan Analysis Dashboard** is a data analytics and business intelligence project developed using Microsoft Power BI. This project focuses on analyzing bank loan data to understand loan application trends, funded amounts, repayment performance, borrower characteristics, and overall lending activities.

The dashboard converts raw banking data into meaningful visual insights, helping stakeholders monitor key performance indicators (KPIs), identify lending patterns, and make data-driven business decisions.

## 🎯 Business Objectives

* Analyze total loan applications and their distribution.
* Monitor the total amount funded and the amount received from borrowers.
* Evaluate loan performance based on loan status.
* Compare good loans and bad loans.
* Understand lending patterns across different loan purposes and borrower segments.
* Analyze changes in loan applications over time.
* Present important banking metrics through interactive visualizations.

## 🛠️ Tools & Technologies

| Tool               | Purpose                                  |
| ------------------ | ---------------------------------------- |
| Microsoft Power BI | Interactive dashboard development        |
| Power Query        | Data cleaning and transformation         |
| DAX                | KPI calculations and analytical measures |
| Data Visualization | Presenting trends and business insights  |
| Excel / CSV        | Data source, if applicable               |

## 📊 Key Performance Indicators (KPIs)

The following KPIs are relevant to bank loan analysis and should be included where supported by the dataset.

### 1. Total Loan Applications

Measures the total number of loan applications received during the selected period.

### 2. Total Funded Amount

Represents the total amount of money distributed to borrowers through approved loans.

### 3. Total Amount Received

Measures the total amount received from borrowers through repayments.

### 4. Average Interest Rate

Shows the average interest rate associated with the loans in the dataset.

### 5. Average Debt-to-Income Ratio

Measures the average DTI ratio, which indicates the relationship between borrowers' debt obligations and income.

### 6. Good Loan Analysis

Examines loans classified as performing or good loans, based on the dataset's loan status definitions.

### 7. Bad Loan Analysis

Examines loans classified as non-performing or bad loans, based on the dataset's loan status definitions.

## 📈 Dashboard Analysis

### A. Summary Analysis

The summary dashboard provides an overview of the bank's lending activities through important KPIs and loan performance metrics.

Key areas of analysis:

* Total loan applications.
* Total funded loan amount.
* Total amount received.
* Average interest rate.
* Average DTI ratio.
* Good loan and bad loan performance.

### B. Loan Status Analysis

This analysis evaluates loan distribution and performance by loan status.

Possible categories include:

* Fully Paid
* Current
* Charged Off

The analysis helps understand the proportion of loans that have been repaid, remain active, or have been charged off.

### C. Loan Purpose Analysis

This analysis explores the reasons borrowers apply for loans.

Possible categories include:

* Debt consolidation
* Credit card repayment
* Home improvement
* Major purchases
* Medical expenses
* Other personal expenses

It helps identify common borrowing purposes and patterns in lending demand.

### D. Borrower Profile Analysis

This section explores loan distribution across borrower characteristics available in the dataset, such as:

* Employment length
* Home ownership
* Annual income
* Loan grade
* Loan term
* Debt-to-income ratio

These factors can help stakeholders understand the borrower segments represented in the portfolio.

### E. Time-Based Analysis

Time-based analysis examines how loan applications and lending activity change over time.

Possible metrics include:

* Monthly loan applications.
* Monthly funded amounts.
* Monthly repayment amounts.
* Changes in loan demand across reporting periods.

## 🔍 Business Questions

This project can help answer the following questions:

1. How many loan applications were received?
2. What is the total amount funded by the bank?
3. What is the total amount received through loan repayments?
4. What is the average interest rate on loans?
5. What percentage of loans are classified as good loans?
6. What percentage of loans are classified as bad loans?
7. Which loan purposes account for the largest number of applications?
8. How does loan performance vary by loan status?
9. How does loan activity change over time?
10. How do borrower characteristics relate to lending patterns?

## 🧹 Data Preparation

Data preparation is an important part of the analytics process. Depending on the source data and the transformations implemented, the workflow may include:

* Importing the dataset into Power BI.
* Checking column names and data types.
* Identifying missing or inconsistent values.
* Removing duplicate records where appropriate.
* Standardizing categorical values.
* Creating calculated columns or measures where necessary.
* Validating totals and KPI calculations before building visualizations.

## 🧮 DAX Measures

Examples of DAX measures that can be used in a bank loan analysis project are provided below. Adjust the table and column names to match your actual data model.

**Total Loan Applications**

```dax
Total Loan Applications =
COUNTROWS('Bank_Loan_Data')
```

**Total Funded Amount**

```dax
Total Funded Amount =
SUM('Bank_Loan_Data'[loan_amount])
```

**Total Amount Received**

```dax
Total Amount Received =
SUM('Bank_Loan_Data'[total_payment])
```

**Average Interest Rate**

```dax
Average Interest Rate =
AVERAGE('Bank_Loan_Data'[int_rate])
```

**Average DTI Ratio**

```dax
Average DTI Ratio =
AVERAGE('Bank_Loan_Data'[dti])
```

*Note: These are example measures, not verified extracts from the uploaded Power BI file. The table name and column names may need to be changed.*

## 📉 Expected Business Value

The dashboard is designed to support:

* Better visibility into lending activities.
* Faster monitoring of loan-related KPIs.
* Improved understanding of loan portfolio composition.
* Identification of patterns in repayment performance.
* Clearer communication of business insights through visual reports.
* Data-driven discussions about lending performance and risk.

The dashboard provides descriptive analysis and should not be treated as a standalone credit approval or risk prediction system.

## 💻 Skills Demonstrated

Through this project, the following data analytics skills can be demonstrated:

* Data cleaning and transformation.
* Exploratory data analysis.
* Power Query.
* DAX measures and calculations.
* KPI tracking.
* Data visualization.
* Dashboard design.
* Business problem analysis.
* Analytical thinking.
* Communicating data-driven insights.

## 📂 Project Structure

```text
bank-loan-analysis-power-bi/
│
├── bank_loan_bi.pbix
├── README.md
└── dataset/                 # Optional: add the dataset if permitted
```

## 🚀 How to Run the Project

1. Download or clone this repository from GitHub.
2. Install Microsoft Power BI Desktop.
3. Download the `bank_loan_bi.pbix` file.
4. Open the file using Power BI Desktop.
5. If prompted, configure the data source or refresh the data.
6. Explore the dashboard pages, charts, filters, and KPIs.

## 📸 Dashboard Preview

Add screenshots of your actual Power BI dashboard to make the GitHub repository more attractive and easier to understand.

For example, save your screenshots in an `images` folder and insert them using Markdown:

```markdown
![Bank Loan Dashboard](images/bank-loan-dashboard.png)
```

## 📌 Project Limitations

* The quality of insights depends on the accuracy and completeness of the underlying dataset.
* Historical trends do not necessarily predict future loan performance.
* Good loan and bad loan classifications depend on the definitions used in the dataset.
* The dashboard does not independently establish causation between borrower characteristics and loan outcomes.

## 🔮 Future Enhancements

Potential improvements include:

* Adding more detailed time-based comparisons.
* Enhancing dashboard navigation and user experience.
* Introducing additional borrower-segment analysis.
* Integrating updated datasets for periodic reporting.
* Connecting Power BI with SQL databases.
* Adding more detailed loan portfolio risk indicators, where suitable data is available.

## 👩‍💻 About Me

**Sai M | Aspiring Data Analyst**

I am passionate about working with data and transforming raw information into meaningful insights that support better decision-making.

I am continuously developing my skills in data analytics, SQL, Python, Microsoft Excel, and Power BI to solve business problems through data-driven approaches.

### Technical Interests

* Data Analytics
* SQL
* Python
* Microsoft Excel
* Power BI
* Data Visualization
* Business Intelligence

## 🤝 Connect With Me

* **GitHub:** [Add your GitHub profile URL]
* **LinkedIn:** [Add your LinkedIn profile URL]
* **Email:** [Add your professional email address]

## ⭐ Support

If you find this project useful or informative, consider giving this repository a star ⭐ on GitHub.

---

**Thank you for visiting my Bank Loan Analysis Dashboard project!**
