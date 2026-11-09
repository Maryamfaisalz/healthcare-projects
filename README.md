# Pharmaceutical Sales Analysis

## 1. Project Overview

This project focuses on analysing historical pharmaceutical sales data to identify sales trends, understand product-category performance, and explore patterns in pharmaceutical demand over time.

The objective is to transform raw sales data into meaningful business insights that can support better inventory planning, demand forecasting, and data-driven business decisions.

The analysis examines pharmaceutical sales across different ATC (Anatomical Therapeutic Chemical) categories using daily, hourly, weekly, and monthly datasets.

## 2. Business Problem

Pharmaceutical businesses need to understand how demand for different medicine categories changes over time.

Without proper analysis of historical sales data, businesses may face challenges such as:

- Inefficient inventory management.
- Difficulty identifying high-demand medicine categories.
- Seasonal fluctuations in pharmaceutical demand.
- Challenges in anticipating changes in customer demand.

This project investigates historical sales patterns to identify opportunities for improving demand understanding and inventory planning.

## 3. Business Objectives

- Analyse historical pharmaceutical sales trends.
- Identify the highest-performing pharmaceutical categories.
- Examine daily, weekly, monthly, and seasonal sales patterns.
- Understand variations in demand across ATC categories.
- Identify business opportunities through exploratory data analysis.
- Develop actionable recommendations based on analytical findings.
- Present insights through an interactive Power BI dashboard.

## 4. Dataset Description

The project contains four datasets:

| Dataset | Description |
|---|---|
| salesdaily.csv | Daily pharmaceutical sales |
| saleshourly.csv | Hourly pharmaceutical sales |
| salesweekly.csv | Weekly pharmaceutical sales |
| salesmonthly.csv | Monthly pharmaceutical sales |

The datasets contain pharmaceutical sales information across multiple ATC categories.

The daily dataset includes:
- Date
- Pharmaceutical category sales
- Year
- Month
- Hour
- Weekday name

**Dataset Source:** 

## 5. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Analysis and documentation |
| Power BI | Interactive dashboard development |
| Git & GitHub | Version control and project documentation |

## 6. Analytical Methodology

The project follows a structured analytical workflow:

1. Data Understanding
   - Examine dataset structure, columns and data types.
   - Understand the available pharmaceutical categories.

2. Data Cleaning & Preparation
   - Check missing values and duplicate records.
   - Validate data types and date formats.
   - Prepare datasets for analysis.

3. Exploratory Data Analysis (EDA)
   - Analyse pharmaceutical category performance.
   - Identify sales trends over time.
   - Investigate monthly and seasonal patterns.
   - Compare sales across different time periods.

4. Business Insights
   - Identify high-performing categories.
   - Investigate demand fluctuations.
   - Translate analytical findings into business insights.

5. Power BI Dashboard
   - Develop KPIs and interactive visualizations.
   - Present sales trends and category performance.
   - Communicate actionable business insights.

## 7. Key Business Questions

1. Which pharmaceutical categories contribute the most to total sales?
2. How does pharmaceutical demand change over time?
3. Which months demonstrate higher pharmaceutical sales?
4. Are there identifiable seasonal patterns in medicine demand?
5. Which pharmaceutical categories demonstrate consistent demand?
6. How can historical sales trends support inventory planning?

## 8. Preliminary Findings

Based on the initial exploratory analysis of the daily dataset:

- N02BE represents approximately 49.38% of total recorded sales across the analysed ATC categories.
- N05B is the second-largest category, contributing approximately 14.61%.
- R03 demonstrates higher average monthly sales during winter months compared with summer months in the initial analysis.

These findings will be further investigated and translated into business recommendations.

## 9. Business Recommendations

Potential recommendations to investigate further include:

- Prioritising inventory monitoring for high-demand pharmaceutical categories.
- Considering seasonal demand patterns when planning medicine stock levels.
- Monitoring changes in category-level sales to identify unusual demand fluctuations.
- Using historical sales trends to support inventory planning and forecasting.

Recommendations will be refined following the completion of the analysis.

## 10. Power BI Dashboard

**Status:** Planned

The final dashboard will include:

- Overall pharmaceutical sales KPIs.
- Category-wise sales performance.
- Monthly and seasonal sales trends.
- Time-based sales comparisons.
- Interactive filters for exploring pharmaceutical categories and periods.


## 11. Repository Structure

```text
pharmaceutical-sales-analysis/
│
├── Datasets/
│   ├── salesdaily.csv
│   ├── saleshourly.csv
│   ├── salesmonthly.csv
│   └── salesweekly.csv
│
├── Python/
│   └── pharmaceutical_sales_analysis.ipynb
│
└── README.md
```

## 12. Limitations & Future Improvements

- Extend the analysis with additional business-relevant datasets.
- Investigate demand forecasting opportunities.
- Develop a more comprehensive ETL workflow.
- Explore SQL-based data analysis.
- Build an interactive Power BI dashboard.
- Improve the analysis with additional business context and validation.

---

**Author:** Maryam Faisal
