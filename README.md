# Final-Project-Bootcamp-Data-Analyst

RappiPlus E-commerce Analytics — Final Bootcamp Project

📌 Project Overview

This project was developed as the final project of the TripleTen Data Analyst Bootcamp. It focuses on analyzing the performance of a fictional e-commerce platform, RappiPlus, by transforming raw data into actionable business insights.

The project covers the end-to-end data analytics workflow, from data quality assessment and preparation to business performance analysis, user behavior analysis, A/B testing, and dashboard development.

The main objective is to support data-driven decision-making by identifying profitability drivers, conversion funnel drop-offs, user retention patterns, and opportunities to improve the customer experience.

🎯 Business Objectives

Ensure data quality and prepare reliable datasets for analysis.

Evaluate business profitability using revenue, costs, and profit metrics.

Analyze the conversion funnel and identify the stages with the highest user drop-off.

Measure user retention through cohort analysis.

Evaluate the impact of product changes using A/B testing.

Consolidate analytical findings into a dashboard to communicate business insights.

🛠️ Tools & Technologies

Python: Data cleaning, exploratory data analysis, business metrics, and A/B testing.

Pandas: Data manipulation, transformation, and preparation.

SQL: Conversion funnel analysis, cohort analysis, and querying relational datasets.

Jupyter Notebook: Analytical workflow and database connectivity.

Power BI / Dashboarding: Visual representation of business performance and analytical findings.

Note: Keep Power BI in this list if it was the tool you used to build the final dashboard.

📊 Project Workflow

1. Data Preparation and Quality Assessment — Python

Business question: Are the datasets reliable enough to support business decisions?

Examined raw datasets to assess data quality.

Identified inconsistencies and prepared the data for analysis.

Cleaned and structured three datasets:

rappiplus_orders_raw.csv

rappiplus_catalog.csv

rappiplus_marketing_spend.csv

Prepared clean datasets for downstream analysis.

Deliverable: Three cleaned datasets ready for analysis.

2. Business Profitability Analysis — Python

Business question: Is the business generating profits, and which segments perform best?

Calculated key business performance indicators, including revenue, costs, and profit.

Combined order information with product catalog data to derive order costs.

Examined business performance across relevant segments.

Identified opportunities to better understand the drivers of profitability.

3. Conversion Funnel Analysis — SQL

Business question: At which stage of the customer journey do users abandon the purchasing process?

Queried event-level data stored in a database.

Analyzed user interactions throughout the conversion funnel.

Evaluated conversion between stages.

Identified the largest drop-off points in the purchasing journey.

Dataset: events

4. User Retention and Cohort Analysis — SQL

Business question: Do users return to the platform after registering, or do they become inactive?

Combined user registration and activity data.

Grouped users into cohorts based on registration timing.

Analyzed activity patterns over time.

Evaluated retention behavior and identified relevant patterns in user engagement.

Datasets: users and user_activity

5. A/B Testing — Python

Business question: Did the changes introduced to the checkout interface have a measurable impact on conversion?

Compared the control and treatment variants.

Analyzed conversion outcomes across experimental groups.

Evaluated the experiment results to assess the impact of the product change.

Developed a recommendation based on the analytical findings.

Dataset: experiment_checkout_ui.csv

6. Dashboard Development and Insights Communication

Business objective: Make the analysis accessible and useful for business stakeholders.

Integrated relevant cleaned datasets.

Structured the data model to maintain consistent relationships and avoid unintended duplication.

Translated analytical results into visualizations.

Consolidated business performance indicators and findings into a final dashboard.

Deliverable: Final business intelligence dashboard.

📈 Key Skills Demonstrated

Data cleaning and data quality assessment

Exploratory data analysis

Business KPI calculation

Revenue, cost, and profitability analysis

SQL querying and relational data analysis

Conversion funnel and drop-off analysis

Cohort-based retention analysis

A/B testing and experiment evaluation

Data visualization and dashboard development

Business insight communication and analytical recommendations
