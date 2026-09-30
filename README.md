# Data Analysis Projects

A collection of end-to-end **Data Analysis, Exploratory Data Analysis, Business Analysis, and Data Visualization projects** created using Python, SQL, Microsoft Excel, and Power BI.

These projects cover different real-world domains such as e-commerce, entertainment, customer behavior, restaurants, and employee attendance.

The main objective of these projects is to demonstrate the complete data analysis process:

* Data Collection
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Statistical Analysis
* Business Analysis
* Data Visualization
* Dashboard Development
* Insight Generation
* Business Decision Support

---

# Projects Included

| No. | Project                          | Domain            | Main Tools                                 |
| --- | -------------------------------- | ----------------- | ------------------------------------------ |
| 1   | Madhav E-Commerce Sales Analysis | E-Commerce        | Power BI, Excel, DAX                       |
| 2   | Netflix EDA                      | Entertainment     | Python, Excel, SQL, Power BI               |
| 3   | Telco Customer Churn Analysis    | Telecom           | Python, Pandas, Seaborn, Matplotlib, TCA   |
| 4   | Zomato EDA                       | Food & Restaurant | Python, Pandas, NumPy, Matplotlib, Seaborn |
| 5   | Atliq HR Presence Analysis       | Human Resources   | Power BI, Excel, DAX                       |

---

# 1. Madhav E-Commerce Sales Analysis

## Overview

The **Madhav E-Commerce Sales Analysis** project analyzes an e-commerce business's sales, profit, customers, products, payment methods, and geographical performance.

The project uses Power BI to convert raw sales data into an interactive dashboard that can be used to understand business performance and identify important sales and profit trends.

## Objectives

The major objectives of the analysis are:

* Analyze overall sales performance
* Analyze total profit
* Understand product category performance
* Identify high-performing states
* Analyze customer spending
* Analyze payment methods
* Study monthly profit trends
* Analyze product sub-categories
* Compare quarterly performance
* Identify areas that can support business decisions

## Key Metrics

The dashboard contains the following major KPIs:

* **Total Revenue:** 438K
* **Total Profit:** 37K
* **Units Sold:** 5,615
* **Average Order Value:** 121K

## Analysis Performed

### 1. State-wise Sales Analysis

Sales performance was analyzed across different Indian states.

The analysis helps identify states contributing significantly to overall sales and provides geographical insight into the business.

### 2. Customer Analysis

Customer-level sales were analyzed to identify customers with higher spending and understand customer contribution to overall revenue.

### 3. Product Category Analysis

The dashboard analyzes product categories and their contribution to the overall quantity sold.

Clothing represents a major share of the quantity sold in the analyzed data.

### 4. Payment Mode Analysis

Different payment methods were analyzed, including:

* Cash on Delivery
* UPI
* Credit Card
* Debit Card
* EMI

The analysis helps understand customer payment preferences.

### 5. Monthly Profit Analysis

Monthly profit trends were analyzed to understand how profitability changes over time.

### 6. Product Sub-category Analysis

Profitability was analyzed across different product sub-categories such as:

* Bottomwear
* Accessories
* Other product segments

### 7. Quarterly Analysis

The dashboard provides a quarter-level analysis covering:

* Q1
* Q2
* Q3
* Q4

A quarter selector allows users to analyze the dashboard for different periods.

## Dashboard Features

* Interactive KPI cards
* Quarter selection
* State-wise sales visualization
* Customer-wise sales analysis
* Category analysis
* Payment-mode analysis
* Monthly profit trend
* Sub-category profit analysis

## Files

```text
MADHAV ECOMMERCE STORE EDA/
│
├── Details.csv
├── Orders.csv
├── FINAL MADHAV ECOMMERCE SALES DASHBOARD.pbix
├── guide_madhavEcommerceStore.pdf
├── bg.jpg
└── README.md
```

## Technologies

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* CSV

---

# 2. Netflix Exploratory Data Analysis

## Overview

The **Netflix EDA** project performs a detailed exploratory analysis of Netflix's content catalog.

The same dataset was analyzed using multiple data analysis tools:

* Python
* Microsoft Excel
* SQL
* Power BI

This makes the project useful for demonstrating how the same business dataset can be explored from different analytical perspectives.

## Dataset

The primary dataset is:

```text
netflix_titles.csv
```

The dataset contains information about Netflix movies and TV shows, including:

* Title
* Content type
* Director
* Cast
* Country
* Date added
* Release year
* Rating
* Duration
* Listed genres
* Description

---

## Python Analysis

Python was used for exploratory data analysis and data cleaning.

### Analysis Performed

#### Content Type Analysis

The number of:

* Movies
* TV Shows

was compared to understand the composition of Netflix's content catalog.

#### Yearly Contribution

The number of Netflix titles added/released across different years was analyzed to identify yearly trends.

#### Top Genres

The top 10 genres contributing the most content were analyzed.

#### Top Countries

Countries contributing the highest number of Netflix titles were identified.

#### Ratings Analysis

The occurrence of different Netflix content ratings was analyzed.

#### Movie Duration

The duration of movies was analyzed to understand the distribution of movie lengths.

## Excel Analysis

Python was used for data cleaning before the cleaned dataset was analyzed in Excel.

The Excel analysis includes:

* Content-type contribution
* Ratings analysis
* Genre-wise contribution
* Monthly contribution
* Yearly trends
* Director-wise contribution
* Country-wise contribution

### Excel Files

```text
cleaning_netflix_for_Excel.ipynb
netflix_cleaned_for_excel.csv
netflix_eda_for_excel.xlsx
```

## SQL Analysis

SQL was used to answer analytical questions from the Netflix dataset.

The analysis includes:

* Total number of movies
* Total number of TV shows
* Countries with the highest contribution
* Years with the highest contribution
* Most common ratings
* Top 10 genres
* Top 5 longest movies
* Directors contributing the most content
* Yearly trends

## Power BI Analysis

Power BI was used to create visual analysis of Netflix content.

The dashboard/report covers:

* Yearly trends
* Movie vs TV show contribution
* Genre contribution
* Ratings
* Country-wise contribution

## Project Structure

```text
NETFLIX EDA/
│
└── NETFLIX EDA/
    │
    ├── IN MS EXCEL/
    │   ├── FINAL EXCEL EDA FOR NETFLIX.docx
    │   ├── FINAL EXCEL EDA FOR NETFLIX.pdf
    │   ├── cleaning_netflix_for_Excel.ipynb
    │   ├── netflix_cleaned_for_excel.csv
    │   ├── netflix_eda_for_excel.xlsx
    │   └── netflix_titles.csv
    │
    ├── IN POWERBI/
    │   ├── FINAL POWERBI NETFLIX EDA.pdf
    │   ├── netflix_powerbi_eda.pbix
    │   └── netflix_titles.csv
    │
    ├── IN PYTHON/
    │   ├── netflix-python-eda.pdf
    │   ├── netflix_cleaned.csv
    │   ├── netflix_python_eda.ipynb
    │   └── netflix_titles.csv
    │
    ├── IN SQL/
    │   ├── final_sql_netflix_eda.ipynb
    │   ├── final_sql_netflix_eda.pdf
    │   └── netflix_titles.csv
    │
    ├── PROJECT GUIDE/
    │   ├── NETFLIX EDA PROJECT GUIDE.docx
    │   └── NETFLIX EDA PROJECT GUIDE.pdf
    │
    └── README.md
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Microsoft Excel
* Power Query
* SQL
* Microsoft Power BI
* DAX

---

# 3. Telco Customer Churn Analysis

## Overview

The **Telco Customer Churn Analysis** project analyzes customer data from a telecommunications context.

The project combines:

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Transductive Component Analysis

The main objective is to explore customer-related data and demonstrate the application of **Transductive Component Analysis (TCA)** for domain adaptation.

## Dataset

The dataset used is:

```text
Customer Churn.csv
```

## Data Cleaning

The project performs preprocessing before analysis.

Major preprocessing activities include:

* Handling blank values
* Handling zero-tenure records
* Converting data types
* Handling missing values
* Preparing the dataset for further analysis

## Exploratory Data Analysis

Python libraries are used to understand the structure and characteristics of the dataset.

EDA includes:

* Dataset inspection
* Missing-value analysis
* Variable analysis
* Distribution analysis
* Relationship analysis
* Data visualization

## Data Visualization

The project uses:

* Matplotlib
* Seaborn

for visualizing patterns and relationships within the dataset.

## Transductive Component Analysis

A major component of this project is **Transductive Component Analysis (TCA)**.

TCA is a domain adaptation technique used to learn a common lower-dimensional representation for data coming from different domains.

The project demonstrates the application of TCA after the initial data preparation and exploratory analysis.

## Workflow

```text
Raw Customer Data
        |
        v
Data Cleaning
        |
        v
Data Preprocessing
        |
        v
Exploratory Data Analysis
        |
        v
Visualization
        |
        v
Transductive Component Analysis
        |
        v
Domain Adaptation Analysis
```

## Files

```text
TELCO CUSTOMER CHURN EDA/
│
└── TELCO CUSTOMER CHURN ANALYSIS/
    │
    ├── Customer Churn.csv
    ├── TCA.ipynb
    ├── TCA.pdf
    └── README.md
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 4. Zomato Exploratory Data Analysis

## Overview

The **Zomato EDA** project performs exploratory data analysis on restaurant-related data.

The analysis focuses on understanding restaurant characteristics, ratings, customer votes, locations, cuisines, pricing, and ordering facilities.

## Objectives

The project aims to analyze:

* Restaurant ratings
* Number of votes
* Restaurant types
* Restaurant locations
* Average cost
* Online ordering
* Table booking
* Cuisines
* Other restaurant-related characteristics

## Data Cleaning

The dataset requires preprocessing before performing EDA.

The analysis includes:

* Handling missing values
* Checking data types
* Cleaning inconsistent values
* Preparing categorical variables
* Preparing numerical variables
* Removing unnecessary information where required

## Exploratory Data Analysis

The project explores multiple aspects of the restaurant dataset.

### Restaurant Ratings

Restaurant ratings are analyzed to understand the distribution of ratings across restaurants.

### Customer Votes

The number of votes received by restaurants is analyzed to understand customer engagement.

### Restaurant Types

Different restaurant types are compared to understand their contribution to the dataset.

### Location Analysis

Restaurant locations are analyzed to identify areas with different levels of restaurant activity.

### Cost Analysis

Average cost information is explored to understand restaurant pricing patterns.

### Online Ordering

Restaurants are analyzed based on whether online ordering is available.

### Table Booking

The availability of table booking is analyzed.

### Cuisine Analysis

Different cuisines are explored to understand their occurrence and distribution.

## Visualizations

The project uses visualizations to identify:

* Distributions
* Comparisons
* Relationships
* Restaurant trends
* Customer behavior patterns

## Project Structure

```text
Zomato EDA Project in Python/
│
├── ZomatoCompany.jpg
├── zomato-analysis.ipynb
├── zomato-analysis.pdf
└── zomato_dataset.zip
```

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 5. Atliq HR Presence Analysis

## Overview

The **Atliq HR Presence Analysis** project analyzes employee attendance and workplace presence data for Atliq employees.

The dataset covers:

* April 2022
* May 2022
* June 2022

The project focuses on employee presence, work-from-home behavior, sick leave, working days, and attendance trends.

## Objectives

The main objectives are:

* Analyze employee presence
* Analyze work-from-home patterns
* Analyze sick leave
* Compare monthly attendance
* Analyze employee attendance
* Analyze day-of-week patterns
* Calculate attendance-related KPIs
* Identify trends in workplace presence

## Key KPIs

The dashboard calculates:

### Total Working Days

The total number of working days is calculated after excluding non-working days.

### Present Days

Present days include employees marked as present along with applicable work-from-home days.

### Presence %

Measures the percentage of employee working days represented by presence.

### Work From Home %

Measures the proportion of workdays represented by work-from-home activity.

### Sick Leave %

Measures sick leave in relation to total working days.

## DAX Measures

### WFH %

```DAX
WFH % =
DIVIDE(
    [WFH Count],
    [Present Days],
    0
) * 100
```

### WFH Count

```DAX
WFH Count =
SUM('Final Data'[WFH Count])
```

### Sick Leave Count

```DAX
SL Count =
SUM('Final Data'[SL Count])
```

### Sick Leave %

```DAX
SL % =
DIVIDE(
    [SL Count],
    [Total Working Days],
    0
) * 100
```

### Present Days

```DAX
Present Days =
VAR Presentdays =
    CALCULATE(
        COUNT('Final Data'[Value]),
        'Final Data'[Value] = "P"
    )

RETURN
    Presentdays + [WFH Count]
```

### Presence %

```DAX
Presence % =
DIVIDE(
    [Present Days],
    'Measure Table'[Total Working Days],
    0
) * 100
```

## Calculated Columns

### WFH Count

```DAX
WFH Count =
SWITCH(
    TRUE(),
    'Final Data'[Value] = "WFH", 1,
    'Final Data'[Value] = "HWFH", 0.5,
    0
)
```

### Sick Leave Count

```DAX
SL Count =
SWITCH(
    TRUE(),
    'Final Data'[Value] = "SL", 1,
    'Final Data'[Value] = "HSL", 0.5,
    0
)
```

### Month

```DAX
Month =
FORMAT(
    'Final Data'[Date],
    "MMMM"
)
```

### Day of Week

```DAX
Day of week =
FORMAT(
    'Final Data'[Date],
    "ddd"
)
```

## Analysis Performed

### Monthly Presence

Employee presence was analyzed separately for:

* April
* May
* June

and across the complete three-month period.

### Work From Home Analysis

The project analyzes how frequently employees worked from home and how WFH behavior changed over the analyzed period.

### Sick Leave Analysis

Sick leave was analyzed across employees and dates to identify attendance patterns.

### Employee-level Analysis

Attendance behavior was analyzed by employee code.

### Day-of-Week Analysis

Presence, work-from-home, and sick-leave patterns were analyzed by day of the week.

## Trends Identified

The project documents the following observations:

* Sick leaves increase over the analyzed period.
* Presence percentage decreases over time.
* Work-from-home behavior is an important component of employee attendance.

## Files

```text
codebasics HR PROJECT/
│
└── codebasics HR PROJECT/
    │
    ├── Attendance-Sheet-2022-2023.xlsx
    ├── Self HR-Analytics Project.pbix
    ├── FINAL DASHBOARD IMAGE.png
    ├── Atliq HR Presence Insights Dashboard.docx
    ├── Atliq HR Presence Insights Dashboard.pdf
    └── README.md
```

## Technologies

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Visualization
* HR Analytics

---

# Tools & Technologies Used Across Projects

## Programming & Data Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Database & Querying

* SQL

## Spreadsheet Analysis

* Microsoft Excel
* Excel data cleaning
* Excel-based analysis

## Business Intelligence & Visualization

* Microsoft Power BI
* Power Query
* DAX
* Interactive dashboards
* KPI analysis
* Business reporting

## Statistical / Analytical Techniques

* Exploratory Data Analysis
* Descriptive analysis
* Data cleaning
* Data preprocessing
* Distribution analysis
* Trend analysis
* Comparative analysis
* Domain adaptation using TCA

---

# General Data Analysis Workflow

The projects in this repository follow a practical data analysis workflow:

```text
             Raw Dataset
                  |
                  v
        Data Understanding
                  |
                  v
           Data Cleaning
                  |
                  v
        Data Preprocessing
                  |
                  v
     Exploratory Data Analysis
                  |
                  v
      Statistical / Business
             Analysis
                  |
                  v
        Data Visualization
                  |
                  v
       Insight Generation
                  |
                  v
       Business Decisions
```

---

# Business Questions Addressed

These projects demonstrate how data analysis can answer practical business questions such as:

### E-Commerce

* How much revenue is being generated?
* Which states contribute most to sales?
* Which customers contribute more revenue?
* Which categories sell the most?
* Which payment methods are commonly used?
* How does profit change over time?

### Entertainment

* What type of content dominates the Netflix catalog?
* Which countries contribute the most content?
* Which genres are most common?
* How has content changed over the years?
* Which ratings occur most frequently?
* Which movies have longer durations?

### Telecom

* What patterns exist in customer data?
* How should missing and inconsistent data be handled?
* What patterns can be identified through exploratory analysis?
* How can domain adaptation techniques be applied to customer datasets?

### Restaurants

* What are the common restaurant ratings?
* Which restaurant types are common?
* Which locations contain more restaurants?
* How does restaurant cost vary?
* How common is online ordering?
* How common is table booking?
* Which cuisines appear most frequently?

### Human Resources

* How many working days are recorded?
* What percentage of days are employees present?
* How frequently do employees work from home?
* How frequently is sick leave taken?
* How do attendance patterns change over time?
* How does attendance vary by day of the week?

---

# Repository Structure

```text
DataAnalysisProjects-main/
│
├── MADHAV ECOMMERCE STORE EDA/
│
├── NETFLIX EDA/
│
├── TELCO CUSTOMER CHURN EDA/
│
├── Zomato EDA Project in Python/
│
├── codebasics HR PROJECT/
│
├── ALL DataAnalytics PROJECTS GUIDE.pdf
│
├── BUSINESS DECISIONS MADE FOR ALL EDA PROJECTS.pdf
│
└── .gitignore
```

---

# Skills Demonstrated

Through these projects, the following practical data analysis skills are demonstrated:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Python Data Analysis
* SQL Analysis
* Excel Analysis
* Power BI Dashboard Development
* DAX
* Power Query
* Data Visualization
* KPI Development
* Trend Analysis
* Customer Analysis
* Sales Analysis
* HR Analytics
* Business Analysis
* Statistical Thinking
* Insight Generation
* Business Decision Support

---

# Project Objective

The overall objective of this repository is to demonstrate the ability to take real-world datasets, clean and analyze them, visualize important patterns, and convert the results into meaningful insights.

The projects cover multiple domains and demonstrate practical usage of Python, SQL, Excel, and Power BI for data analysis.

---

# Author

**Om Satyawan Pathak**

Data Analysis | Python | SQL | Excel | Power BI
Email: omsatyawanpathakgit@gmail.com
