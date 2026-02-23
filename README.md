# Hospital Quality & Readmission Analysis

## Overview
This project analyzes hospital quality and readmission metrics reported by the Centers for Medicare & Medicaid Services (CMS). 
The goal is to identify high-risk hospitals, explore relationships between patient experience and outcomes, and surface insights 
that could support healthcare quality improvement initiatives.

## Business Questions
- Which hospitals have the highest readmission rates?
- How do readmissions vary by state and hospital ownership?
- Are patient satisfaction scores associated with readmission outcomes?
- Which hospitals consistently underperform quality benchmarks?

## Data Sources
Data for this project comes from the Centers for Medicare & Medicaid Services (CMS) Hospital Compare / Quality of Care datasets, including:
- Hospital General Information
- Readmissions and Deaths
- Patient Survey (HCAHPS)

These datasets contain hospital-level quality metrics, patient outcomes, and patient experience measures for hospitals across the United States.

## Tools & Skills
- SQL (data cleaning, joins, CTEs, window functions)
- Data modeling (fact and dimension tables)
- Healthcare quality metrics analysis
- BI-style summary tables
- Data visualization (Power BI / Tableau)
- Analytical storytelling and recommendations

## Project Workflow
1. Loaded raw CMS hospital datasets into a SQL database
2. Performed data profiling and quality checks
3. Cleaned and standardized hospital, readmission, and patient survey data
4. Modeled data using fact and dimension tables
5. Built SQL summary tables for BI analysis
6. Developed a dashboard to visualize key quality and readmission trends
7. Delivered insights and recommendations based on findings

## Key Insights
- Certain hospitals consistently exhibit higher readmission rates across multiple conditions
- Readmission rates vary significantly by state and hospital ownership type
- Lower patient satisfaction scores are associated with higher readmission risk

- ## Repository Structure
- hospital-quality-analysis/
├── sql/            # Data cleaning, modeling, and analysis queries
├── dashboard/      # Dashboard screenshots or BI files
├── insights/       # Executive summary and findings
├── data/           # Raw data files (if permitted)
└── README.md

## How to Use This Project
1. Review SQL scripts in the `sql/` folder to see data cleaning and analysis logic
2. View the dashboard in the `dashboard/` folder for visual insights
3. Read the executive summary in `insights/` for high-level findings and recommendations

## Future Improvements
- Add year-over-year trend analysis
- Develop a composite hospital quality score
- Incorporate additional CMS outcome measures
- Expand dashboard interactivity
