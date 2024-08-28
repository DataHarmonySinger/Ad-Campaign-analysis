# Ad-Campaign-analysis
# Ad Campaign Performance Analysis

## Project Overview

This project showcases a comprehensive analysis of ad campaigns from Facebook and Google Ads using Python, SQL, and Looker Studio. The primary goal was to extract valuable insights from the data and present them in a clear, actionable format. The project involves data cleaning, preparation, analysis, and visualization.

## Files in the Repository

1. **Python Report**: 
   - **Filename**: `python_report.ipynb`
   - **Description**: This notebook contains the Python code used for data cleaning, preparation, and initial analysis. It includes steps to handle missing values, create new data points like CTR and CVR, and convert Excel files to CSV format for easier integration with BigQuery.

2. **SQL Codes**:
   - **Filename**: `sql_queries.sql`
   - **Description**: The SQL file contains all the queries used in Google BigQuery to analyze the cleaned data. These queries calculate key performance metrics like Total Impressions, Total Spend, CTR, and CPA, comparing the effectiveness of campaigns across Google Ads and Facebook Ads.

3. **Looker Studio Report**:
   - **Filename**: `looker_studio_report.pdf`
   - **Description**: This file presents the data visualizations created in Looker Studio. The report includes dashboards that display key metrics, helping to visualize the data insights and trends for both ad platforms.

4. **Final Analysis Report**:
   - **Filename**: `final_analysis_report.pdf`
   - **Description**: This document summarizes the entire analysis process, including findings and recommendations. It details the insights gained from the Python and SQL analysis and how the Looker Studio visualizations support these insights.

## Project Workflow

1. **Data Cleaning and Preparation**:
   - Using Python, the dataset was cleaned by handling missing values and creating new metrics to better understand the data.

2. **Data Analysis with SQL**:
   - SQL queries were used in Google BigQuery to perform a deep analysis of the data, extracting key metrics for comparison between platforms.

3. **Data Visualization with Looker Studio**:
   - Looker Studio was used to create dashboards that visually represent the insights, making the data easier to understand for stakeholders.

4. **Final Report**:
   - A comprehensive report was compiled, summarizing the findings and providing actionable recommendations based on the analysis.

## Key Findings

- Google Ads generally performed better across most metrics, particularly in terms of Click-Through Rate (CTR) and Cost Per Acquisition (CPA).
- Specific days of the week showed higher performance, suggesting optimal times for ad spend allocation.
- Recommendations include optimizing budget allocation towards better-performing days and platforms and continuing to monitor performance for dynamic adjustments.

