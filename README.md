# Fitly-User-Activity-Analysis
An analysis of Fitly's user activity, account information, and customer support data using Python.

Fitly User Engagement and Support Analysis


Project Overview

This repository contains a data analytics project centered on Fitly, an active lifestyle application. The primary objective is to investigate the correlations between daily user activity, account subscription structures, and customer support touchpoints. By merging these isolated tracking files, the analysis aims to identify behavioral patterns that influence user retention and platform engagement.
The core analysis is performed in Python within a Jupyter Notebook environment, utilizing standard data science libraries to clean, transform, and visualize the data.

Directory Structure

The repository consists of the following primary components:
• notebook.ipynb contains the complete data pipeline, including data ingestion, exploratory data analysis, visualizations, and statistical summaries.
• da_fitly_user_activity.csv logs daily operational metrics, step counts, and active status tracking for the user base.
• da_fitly_account_info.csv details customer profile attributes, registration timelines, and active subscription tiers.
• da_fitly_customer_support.csv records support ticket histories, resolution durations, and user satisfaction ratings.

Technical Implementation

The analytical workflow utilizes the following python tools:
• Pandas for structured data manipulation, missing value treatment, and outer-join operations across files.
• NumPy for vectorized calculations and conditional logic mapping.
• Matplotlib and Seaborn for generating statistical data visualizations and trend analysis.

Key Operational Insights

The notebook explores three core areas of the business:
• User Activity Trends: Evaluation of active versus inactive patterns over specific timelines to isolate where user drop-off occurs.
• Churn Analysis: Cross-referencing subscription tiers against activity logs to determine if specific account structures experience higher retention rates.
• Support Impact: Analyzing whether extended customer support resolution times directly match lower customer satisfaction scores or increased user inactivity.

Execution Instructions

To replicate the analysis locally:
1. Clone the repository to your environment using a Git terminal.
2. Ensure you have Python installed along with pandas, matplotlib, and seaborn packages.
3. Place all three CSV datasets in the same working directory as the notebook file.
4. Execute the Jupyter Notebook cells sequentially to reproduce the visualizations and summary dataframes.
