# IT-Simplera-Week1-EDA
Week 1 Exploratory Data Analysis (EDA) and Data Preprocessing project on online retail transaction records.
# Week 1: Exploratory Data Analysis (EDA) - Online Retail

## Project Overview
This project focuses on performing deep Exploratory Data Analysis (EDA) on an online retail dataset containing over 525,000 transaction records. The goal is to clean, transform, and visualize the data to extract actionable business insights.

## Environment Setup
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## Key Steps
1. **Cleaning:** Handled missing values and standardized data types.
2. **Preprocessing:** Converted text dates into valid datetime objects.
3. **Feature Engineering:** Calculated total `Revenue` by multiplying `Quantity` and `Price`.
4. **Outlier Detection:** Used Box Plots to identify and isolate wholesale bulk transactions.

## Insights
- **Seasonality:** Identified late winter as the peak sales cycle.
- **Correlation:** Analyzed the linear impact of item `Price` vs `Quantity` on total revenue.

## Repository Contents
- `Week1-EDA-Notebook.ipynb`: Complete data cleaning and analysis code.
- `Week1-EDA-Project.pdf`: Final presentation summarizing the workflow and results.
- `data/`: Folder containing raw data files.
