# 💰 Loan Portfolio Analysis – Power BI Dashboard

An end-to-end **Power BI analytics dashboard** designed to analyze loan portfolio performance across **loan amounts, repayment status, borrower grades, revolving balances, payment behavior, verification status, home ownership, and geographic distribution**.

This project focuses on **data visualization, Power BI data modeling, DAX calculations, interactive reporting, and business-oriented analysis**.

---


## 📌 Project Overview

Loan portfolio data contains valuable information about borrower characteristics, loan performance, payments, and repayment behavior. However, raw loan-level data can be difficult to interpret without proper transformation and visualization.

This project uses **Microsoft Power BI** to transform loan data into an interactive analytical dashboard that helps users understand:

* Loan portfolio size and payment performance
* Loan trends across different years
* Loan distribution by grade and sub-grade
* Revolving balance patterns
* Verification status and customer distribution
* Loan status and repayment performance
* State-wise loan activity
* Home ownership and payment behavior
* Last payment and credit history trends

The dashboard is designed to make the underlying data easier to explore and understand through interactive visuals and filters.

---

## 🎯 Business Objectives

The main objectives of this project are:

* Analyze the overall loan portfolio
* Monitor total loan amounts and payments
* Understand loan performance by status
* Analyze loan distribution across grades and sub-grades
* Identify revolving balance patterns
* Compare loan activity across years
* Analyze verification status
* Understand state-wise loan performance
* Analyze home ownership and payment behavior
* Enable interactive exploration using Power BI filters and slicers

---

## 📂 Dataset Overview

The dataset contains loan-level financial and borrower information.

Important fields used in the analysis include:

* **Loan Amount**
* **Loan Status**
* **Grade**
* **Sub-Grade**
* **Revolving Balance (`revol_bal`)**
* **Total Payment (`total_pymnt`)**
* **Recoveries**
* **Last Payment Amount (`last_pymnt_amnt`)**
* **Issue Date (`issue_d`)**
* **Last Credit Pull Date (`last_credit_pull_d`)**
* **Verification Status**
* **Public Records (`pub_rec`)**
* **State**
* **Term**
* **Home Ownership**

The dataset is analyzed using different dimensions such as **year, state, grade, sub-grade, loan status, and verification status**.

---

# 🧱 Dashboard Structure

The Power BI report contains the following pages:

1. Dashboard
2. Year / Loan Amount
3. Grade / Sub-Grade Wise Revolving Balance
4. Status / Total Payment
5. State-wise Loan Status
6. Home Ownership vs Last Payment Date Statistics
7. State-wise Information
8. Index / Navigation Page

Interactive slicers and navigation buttons are used throughout the report.

---

# 📊 Page-wise Analysis

## 1️⃣ Dashboard

### Purpose

The main dashboard provides a high-level overview of the loan portfolio and combines multiple business metrics into a single analytical view.

### Key KPIs

* **Total Loan Amount**
* **Total Recoveries**
* **Total Last Payment Amount**

### Key Visualizations

* Sub-grade Wise Revolving Balance
* Year-wise Loan Amount
* Status-wise Total Payment
* Home Ownership vs Last Payment Date Statistics
* State-wise Total Payment

### Interactive Filters

* Year
* Grade
* Loan Status

### Business Value

This page provides a quick overview of the overall portfolio and allows users to interactively explore loan performance using key filters.

---

## 2️⃣ Year / Loan Amount

### Purpose

Analyze how loan amounts are distributed across years and loan terms.

### Key Visualizations

* **Year-wise Loan Amount**
* **Term-wise Loan Amount**
* **Status-wise Loan Amount**
* Year-based filtering
* Detailed year and loan amount table

### Business Questions

* How does the loan portfolio change over time?
* Which loan terms account for the largest loan amounts?
* How is loan amount distributed across different loan statuses?

### Business Value

This page helps identify historical patterns and changes in the loan portfolio over time.

---

## 3️⃣ Grade / Sub-Grade Wise Revolving Balance

### Purpose

Analyze revolving balance across borrower credit grades and sub-grades.

### Key Visualizations

* **Sub-grade Wise Revolving Balance**
* **Grade and Sub-grade Wise Revolving Balance %**
* **Grade Wise Revolving Balance**

### Interactive Filter

* Grade

### Business Questions

* Which grades have the highest revolving balances?
* How is revolving balance distributed among sub-grades?
* What percentage of revolving balance is associated with each grade?

### Business Value

This analysis helps understand borrower credit segments and their associated revolving balance patterns.

---

## 4️⃣ Status / Total Payment

### Purpose

Analyze loan repayment performance and payment distribution by verification and loan status.

### Key Visualizations

* Count of verified vs non-verified customers
* Status-wise Total Payment
* Paid Status analysis

### Interactive Filter

* Verification Status

### Business Questions

* How much has been paid across different loan statuses?
* How does verification status relate to customer counts?
* Which loan statuses account for the largest payment amounts?

### Business Value

This page provides visibility into payment behavior and loan repayment performance.

---

## 5️⃣ State-wise Loan Status

### Purpose

Analyze loan performance geographically across different states.

### Key Visualizations

* Verified vs non-verified customer analysis
* State-wise Total Payment
* Paid Status distribution

### Interactive Filters

* Last Credit Pull Date
* State

### Business Questions

* Which states contribute the most to total payments?
* How does loan status vary by state?
* How are verified and non-verified customers distributed?

### Business Value

Geographic analysis helps identify variations in loan activity and repayment behavior across different states.

---

## 6️⃣ Home Ownership vs Last Payment Date Statistics

### Purpose

Analyze payment behavior in relation to borrower home ownership and last payment information.

### Key Analysis

* Home ownership distribution
* Year-wise last payment statistics
* Last payment-related trends
* Detailed supporting table

### Interactive Filters

* Last payment / credit date-related filtering

### Business Questions

* How does home ownership vary across the portfolio?
* How do last payment values change over time?
* Are there visible differences in payment behavior across home ownership categories?

### Business Value

This page provides additional borrower-level context to payment analysis.

---

## 7️⃣ State-wise Information

### Purpose

Provide detailed state-level information about loans and their status.

### Key Visualizations

* Loan Amount by Status
* State selection
* Detailed state-level information table

### Key Fields

* State
* Loan Amount
* Loan Status
* Issue Date

### Business Questions

* What is the total loan amount for each state?
* How does loan status vary by state?
* What are the loan trends across issue dates?

### Business Value

This page supports more detailed state-level analysis and allows users to drill into individual geographic segments.

---

# 🛠 Tools & Technologies Used

* **Microsoft Power BI Desktop**
* **Power Query**
* **DAX (Data Analysis Expressions)**
* Data Modeling
* Interactive Visualizations
* Slicers & Filters
* Power BI Report Navigation
* Time-based Analysis

---

# 📐 Power BI Concepts Used

### Data Preparation

* Data cleaning
* Data type handling
* Date transformation
* Data filtering
* Data preparation using Power Query

### Data Analysis

* Aggregations
* Grouping and segmentation
* Percentage analysis
* Year-wise analysis
* State-wise analysis
* Status-based analysis

### Visualization

* KPI Cards
* Area Charts
* Column Charts
* Bar Charts
* Pie Charts
* Tables
* Slicers

### Dashboard Design

* Interactive navigation
* Page-level analysis
* Consistent layout
* Business-focused KPIs
* Interactive filtering

---

# 📈 Key Analysis Areas

| Area              | Analysis                                     |
| ----------------- | -------------------------------------------- |
| Loan Amount       | Overall and year-wise loan distribution      |
| Loan Status       | Payment and repayment status analysis        |
| Grade             | Grade-wise portfolio analysis                |
| Sub-Grade         | Detailed credit-segment analysis             |
| Revolving Balance | Grade and sub-grade revolving balance        |
| Verification      | Verified vs non-verified customer analysis   |
| Geography         | State-wise loan and payment analysis         |
| Payments          | Total payment and last payment analysis      |
| Term              | Loan amount distribution by term             |
| Home Ownership    | Payment behavior across ownership categories |
| Time              | Year-wise loan and payment trends            |

---

# 💡 Business Insights

The dashboard is designed to help users:

* Monitor overall loan portfolio performance
* Understand repayment and payment patterns
* Identify differences between loan grades and sub-grades
* Analyze geographic loan distribution
* Compare verified and non-verified customers
* Monitor revolving balance across credit segments
* Understand changes in loan amounts over time
* Explore payment behavior across borrower characteristics

---

# 📚 Key Learnings

Through this project, I gained practical experience in:

* Building an end-to-end Power BI dashboard
* Preparing and transforming raw data using Power Query
* Creating interactive visualizations
* Using filters and slicers
* Building business-focused KPIs
* Performing time-based analysis
* Analyzing financial data from multiple dimensions
* Designing dashboards for better data storytelling
* Applying Power BI concepts to a real-world analytical use case

---

# 🚀 Future Enhancements

Possible future improvements include:

* Adding Year-over-Year loan growth analysis
* Adding Month-over-Month payment analysis
* Creating advanced DAX measures
* Adding borrower segmentation
* Adding risk-based analysis
* Adding drill-through pages for detailed borrower analysis
* Adding automated data refresh
* Publishing the dashboard to Power BI Service
* Implementing Row-Level Security where required
* Adding advanced forecasting and predictive analytics

---

# 👤 Author

**Humaira**

Data Analyst | Power BI | SQL | Data Analytics

🔗 **GitHub Project:**
[YOUR_GITHUB_PROJECT_LINK](YOUR_GITHUB_PROJECT_LINK)

🔗 **Live Power BI Dashboard:**
[View Dashboard](YOUR_POWER_BI_LIVE_DASHBOARD_LINK)

---

## 📌 Project Note

This project was created for **learning, portfolio, and demonstration purposes** to showcase practical skills in Power BI, data analysis, data visualization, and dashboard development.

The dashboard demonstrates how raw financial data can be transformed into an interactive analytical solution that supports business-oriented decision-making.
