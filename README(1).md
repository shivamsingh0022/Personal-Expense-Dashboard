# 💰 Personal Expense Dashboard -- Power BI

## 📊 Project Overview

**Personal Expense Dashboard** is an interactive data analytics project
created using **Microsoft Power BI**. The dashboard helps users
understand their personal spending patterns by analyzing expenses across
categories, months, and payment methods.

The project was developed as part of an **internship project** to
demonstrate practical skills in data cleaning, data modeling, DAX, data
visualization, and dashboard design.

------------------------------------------------------------------------

## 🎯 Project Objective

The main objective of this project is to transform raw personal expense
data into an interactive and easy-to-understand dashboard.

The dashboard helps answer questions such as:

-   How much has been spent in total?
-   How many expense transactions are recorded?
-   What is the average expense per transaction?
-   Which categories have the highest expenses?
-   How do expenses change month by month?
-   Which payment methods are used most?
-   How can expenses be filtered by month, category, payment method, and
    date period?

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Microsoft Power BI**
-   **Power Query** -- Data cleaning and transformation
-   **DAX (Data Analysis Expressions)** -- Measures and calculations
-   **Data Visualization** -- Charts, cards, slicers, and tables
-   **CSV Dataset** -- Source data

------------------------------------------------------------------------

## 📁 Dataset

The dashboard is based on a personal expense dataset containing **500
transactions**.

Typical fields used in the analysis include:

-   Date
-   Month
-   Category
-   Amount
-   Payment Method

The dataset contains different expense categories such as:

-   Travel
-   Rent
-   Shopping
-   Education
-   Health
-   Bills
-   Food
-   Entertainment

Payment methods include:

-   Net Banking
-   Debit Card
-   UPI
-   Card
-   Cash

------------------------------------------------------------------------

## 📌 Dashboard KPIs

The dashboard contains the following key performance indicators:

### 1. Total Expense

Displays the total amount spent during the selected date period.

### 2. Total Transaction

Displays the total number of expense transactions.

### 3. Average Expense

Shows the average amount spent per transaction.

These KPI cards provide a quick summary of the user's overall spending.

------------------------------------------------------------------------

## 📈 Dashboard Visualizations

### 🔹 Total 5 Expense by Category

A bar chart showing the top five expense categories based on total
spending.

### 🔹 Expense by Category

A donut chart showing the distribution of expenses across different
categories.

### 🔹 Monthly Expense Trend

A line chart showing how total expenses change over different months.

### 🔹 Total Expense by Payment Method

A pie/donut chart showing the total spending through different payment
methods.

### 🔹 Expense Detail Table

A detailed table displays:

-   Month
-   Category
-   Sum of Amount
-   Payment Method

This allows users to inspect individual expense groups in more detail.

------------------------------------------------------------------------

## 🎛️ Interactive Filters

The dashboard includes interactive slicers and filters:

### Date Period

Allows users to select a custom start and end date.

### Month

Filters the dashboard according to a selected month.

### Category

Filters expenses based on categories such as Travel, Rent, Shopping,
Education, Health, etc.

### Payment Method

Filters expenses according to the selected payment method.

All visuals update dynamically when the filters are changed.

------------------------------------------------------------------------

## 🧮 Example DAX Measures

### Total Expense

``` dax
Total Expense = SUM('Personal Expense'[Amount])
```

### Total Transaction

``` dax
Total Transaction = COUNTROWS('Personal Expense')
```

### Average Expense

``` dax
Average Expense = AVERAGE('Personal Expense'[Amount])
```

> Replace `'Personal Expense'` with the actual table name used in your
> Power BI model if it is different.

------------------------------------------------------------------------

## 🔄 Project Workflow

``` text
Raw CSV Dataset
       ↓
Data Import
       ↓
Data Cleaning using Power Query
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Charts & Visualizations
       ↓
Slicers & Filters
       ↓
Interactive Personal Expense Dashboard
```

------------------------------------------------------------------------

## 🧹 Data Preparation

The data preparation process includes:

1.  Importing the CSV dataset into Power BI.
2.  Checking column names and data types.
3.  Converting the Date column to the correct date format.
4.  Checking missing or invalid values.
5.  Creating/validating the Month field.
6.  Checking expense amounts.
7.  Verifying category and payment method values.
8.  Loading the cleaned data into the Power BI model.

------------------------------------------------------------------------

## 🎨 Dashboard Design

The dashboard uses a modern blue theme with:

-   KPI cards
-   Rounded visual containers
-   Interactive slicers
-   Bar chart
-   Donut charts
-   Line chart
-   Detail table
-   Date-range selection

The layout is designed to provide a quick overview first and detailed
expense information below it.

------------------------------------------------------------------------

## 💡 Key Insights

The dashboard can be used to identify:

-   High-spending categories
-   Monthly spending patterns
-   Average transaction value
-   Total number of transactions
-   Preferred payment methods
-   Changes in spending after applying filters

The exact insights depend on the selected date range, category, month,
and payment method.

------------------------------------------------------------------------

## 📸 Dashboard Preview

Add your Power BI dashboard screenshot to the repository and use:

``` markdown
![Personal Expense Dashboard](images/personal-expense-dashboard.png)
```

Recommended repository structure:

``` text
Personal-Expense-Dashboard/
│
├── README.md
├── dataset/
│   └── Personal_Expense_500_Dataset.csv
│
├── dashboard/
│   └── Personal_Expense_Dashboard.pbix
│
└── images/
    └── personal-expense-dashboard.png
```

------------------------------------------------------------------------

## 🚀 How to Use

1.  Download or clone this repository.
2.  Open the `.pbix` file using **Microsoft Power BI Desktop**.
3.  Check the data source if the CSV path needs to be changed.
4.  Refresh the dataset.
5.  Use the slicers to filter the dashboard.
6.  Explore the charts and expense details.

------------------------------------------------------------------------

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

-   Power BI
-   Power Query
-   DAX
-   Data Cleaning
-   Data Transformation
-   Data Modeling
-   Data Visualization
-   KPI Development
-   Interactive Dashboard Design
-   Business/Data Analysis
-   Slicers and Filters
-   Analytical Reporting

------------------------------------------------------------------------

## 🎓 Internship Project

**Project Type:** Internship Project\
**Domain:** Data Analytics / Business Intelligence\
**Tool:** Microsoft Power BI\
**Dataset Size:** 500 Transactions\
**Project:** Personal Expense Dashboard

This project demonstrates the practical application of Power BI for
converting raw expense data into an interactive analytical report.

------------------------------------------------------------------------

## 👨‍💻 Author

**Shivam Parmar**

BCA Student \| Data Analytics Enthusiast

### Skills

-   Power BI
-   Excel
-   Python
-   SQL
-   Data Analysis
-   Data Visualization

------------------------------------------------------------------------

## ⭐ Project Highlights

-   Interactive Power BI dashboard
-   500 expense transactions
-   KPI-based reporting
-   Category-wise expense analysis
-   Monthly expense trend
-   Payment-method analysis
-   Date-range filtering
-   Dynamic slicers
-   Clean and responsive dashboard layout

------------------------------------------------------------------------

## 📄 License

This project is created for **educational and internship portfolio
purposes**.
