This project is the second part of my Worldwide Layoffs SQL portfolio series. After cleaning the dataset in the first project, I performed exploratory data analysis (EDA) to uncover trends, patterns, and insights using structured SQL queries.

The goal of this project is to explore the global layoffs dataset and answer key analytical questions such as:

-Which companies, industries, and countries experienced the most layoffs?

-When did the layoffs peak?

-Which stages of companies were most affected?

-What does the monthly progression of layoffs look like?

Key Insights & Analysis

1. Total Layoffs Overview

-Checked the maximum total layoffs and percentage laid off.

-Identified companies with 100% layoffs, highlighting full shutdowns.

Company-Level Analysis

-Aggregated total layoffs by company.

-Ranked companies by number of layoffs each year using DENSE_RANK().

2. Date Range and Timeline

-Extracted the earliest and latest dates in the dataset.

-Created a rolling total of monthly layoffs to visualize progression over time.

Country and Industry Breakdown

-Summed layoffs by country and industry to show where impacts were most severe.

3. Stage Analysis

-Evaluated layoffs by company stage (e.g., Series A, B, Public, etc.).

4. Yearly Trends

-Assessed which years had the highest layoff volumes.

-Explored company layoffs per year, ranking top 5 companies annually.

5. Skills Demonstrated

-Data aggregation and grouping

-Temporal analysis using dates and time-based functions

-Window functions for ranking and rolling totals

-Using CTEs to structure complex queries

-Business-focused analytical storytelling with SQL

This project demonstrates how to extract actionable insights from a cleaned dataset using SQL. It answers high-level business questions and supports trend analysis that could guide decision-making for stakeholders or reporting in a business intelligence (BI) environment.
