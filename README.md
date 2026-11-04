# Churn_Analysis_and_Customer_Intelligence_Project
End-to-end Customer Churn Analysis using SQL, Python, Pandas, NumPy and data visualisation to identify customer behaviour, revenue impact and retention opportunities.

# Customer Churn & Customer Intelligence Analysis
### End-to-End Data Analytics Project | SQL + Python

![Python](https://img.shields.io/badge/Python-3.x-blue)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-purple)
![Status](https://img.shields.io/badge/Project-Completed-success)

## Project Overview

Customer retention is a critical factor in the growth and profitability of subscription-based businesses.

This project focuses on analysing customer churn for an OTT subscription platform to understand customer behaviour, identify churn patterns, evaluate revenue impact, and develop data-driven customer retention strategies.

The project follows an end-to-end Data Analytics workflow, integrating SQL databases with Python for data extraction, cleaning, transformation, exploratory data analysis (EDA), KPI development, and data visualisation.

The objective is to transform raw customer and subscription data into meaningful business insights that can support customer retention and revenue optimisation decisions.

## Business Objectives

- Calculate overall customer churn and retention rates.
- Identify customer segments with higher churn rates.
- Analyse churn across subscription plans and contract types.
- Investigate geographical and monthly churn trends.
- Evaluate revenue leakage and Customer Lifetime Value (CLTV) loss.
- Understand the relationship between customer support escalations and churn risk.
- Recommend strategies to improve customer retention.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data analysis and transformation |
| SQL | Data extraction and querying |
| SQLite | Relational database |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive development environment |

## Project Workflow

### 1. SQL Database Integration

- Connected the SQLite database with Python using `sqlite3`.
- Retrieved records using SQL queries.
- Integrated customer, subscription, and support-related information.
- Imported SQL query results into Pandas DataFrames.

### 2. Data Cleaning and Preparation

- Inspected datasets and their structures.
- Checked data types and missing values.
- Renamed and selected relevant columns.
- Performed data quality checks.
- Handled null values and prepared datasets for analysis.

### 3. Feature Engineering

- Created calculated columns.
- Transformed subscription and customer information.
- Developed customer tenure and churn-related attributes.
- Segmented customers based on churn risk.

### 4. Exploratory Data Analysis (EDA)

Performed analytical operations using Pandas and NumPy, including:

- GroupBy and aggregation.
- Pivot tables.
- Customer segmentation.
- Churn analysis by subscription and contract type.
- Geographical churn analysis.
- Revenue and CLTV analysis.
- Customer support and escalation analysis.

### 5. Data Visualisation

Used Matplotlib and Seaborn to explore and communicate:

- Overall churn and retention.
- Monthly churn trends.
- Contract-wise churn distribution.
- Subscription plan performance.
- Revenue impact.
- Customer risk patterns.

## Key Business Insights

The analysis identified the following findings:

| Business Metric | Result |
|---|---:|
| Overall Customer Churn Rate | 28.6% |
| Customer Retention Rate | 71.4% |
| Monthly Contract Churn | 55.6% |
| Annual Contract Churn | 8.3% |
| Average Customer Tenure | 1,451 days |
| Average Revenue Per User (ARPU) | Rs. 18.8 |
| Total Revenue | 395 |
| Revenue Loss Due to Churn | 74 |
| Revenue Loss Percentage | 18% |
| CLTV Lost | 2,047 |

### Important Findings

**1. Contract Type and Customer Churn**

Monthly contract customers demonstrated a significantly higher churn rate (55.6%) compared with annual contract customers (8.3%).

This highlights the importance of contract structure in customer retention.

**2. Subscription Plan Analysis**

The Basic subscription plan contributed the largest share of customer churn. However, the revenue impact should also be considered when prioritising retention efforts.

**3. Geographical Churn Patterns**

Karnataka emerged as the most affected state in the analysis. Further investigation into pricing changes, service quality, and customer complaints could help identify possible reasons.

**4. Monthly Churn Trend**

September 2024 recorded the highest churn activity in the analysed period, suggesting the need to investigate potential pricing, product, or competitive changes during that month.

**5. Revenue and Customer Lifetime Value**

The analysis identified revenue loss of approximately 74 and CLTV loss of 2,047 associated with churned customers.

These findings demonstrate how customer churn can affect recurring revenue and long-term customer value.

*Note: These are findings from the project dataset. Revenue units should be interpreted according to the source dataset.*

## Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Improve Monthly Customer Retention:** Introduce targeted retention campaigns and incentives for monthly subscribers.
2. **Encourage Annual Subscriptions:** Explore suitable annual subscription offers to improve long-term customer commitment.
3. **Investigate High-Churn Regions:** Review pricing, customer complaints, technical issues, and competitor activity in Karnataka.
4. **Prioritise High-Risk Customers:** Identify customers with medium and high churn scores and prioritise them using CLTV.
5. **Improve Customer Support:** Investigate escalated complaints and service issues that may contribute to customer dissatisfaction.
6. **Monitor Revenue Leakage:** Track churn-related MRR and CLTV losses through regular business reporting.

## Project Deliverables

- SQL database integration with Python.
- Data cleaning and quality checks.
- Exploratory Data Analysis.
- Customer segmentation and churn analysis.
- Business KPI calculations.
- Data visualisations.
- Business insights and recommendations.

## Skills Demonstrated

- SQL querying and database integration.
- Python programming.
- Data cleaning and transformation.
- Exploratory Data Analysis.
- Data aggregation and grouping.
- KPI development.
- Customer segmentation.
- Revenue analysis.
- Data visualisation.
- Business problem-solving and analytical storytelling.

## Repository Structure

```text
├── README.md
├── requirements.txt
├── data/
├── notebooks/
├── reports/
├── visualizations/
└── outputs/
```

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/DEEPA-SI/Churn_Analysis_and_Customer_Intelligence_Project.git
```

2. Navigate to the project directory:

```bash
cd Churn_Analysis_and_Customer_Intelligence_Project
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the notebook inside the `notebooks` directory and execute the cells.

*The source SQLite database must be placed in the expected location before running the notebook. Update database paths if necessary.*

## Learning and Project Acknowledgement

This project was developed as part of my practical learning journey in Data Analytics, using an OTT customer churn analysis learning resource by Rishabh Mishra.

The implementation, analysis, and portfolio documentation are intended to demonstrate my learning and application of SQL and Python analytics techniques.

---

### Author

**Deepa Singh**

Master of Applied Technologies – Data Analytics & Intelligence

Interested in Data Analytics, Business Intelligence, SQL, Python, and Data Engineering.

[GitHub Profile](https://github.com/DEEPA-SI)

---

*Turning data into insights and insights into better business decisions.*
