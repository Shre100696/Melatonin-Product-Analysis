# Melatonin Product Analysis on E-Commerce Platforms


## Introduction
This repository provides an in-depth analysis of melatonin products available on an e-commerce platform.
It focuses on customer reviews, ratings, and detailed product information to extract meaningful insights.
The goal is to understand product popularity, customer satisfaction, and identify opportunities for improving data quality.
Dataset Description
The dataset consists of multiple CSV files, with each file corresponding to different melatonin products marked by unique ASINs.
Data has been sourced from various e-commerce platforms and is structured for analysis in pandas DataFrames.



### Analysis Overview
Data Loading: CSV files are read into pandas DataFrames for manipulation.
Initial Exploration: Quick examination of the datasets including row/column counts and previewing data using DataFrame.head().
Data Quality Assessment: Identification of missing values in the dataset.
Visualization: Use seaborn's displot to showcase the distribution of missing data.
Data Concatenation: Merge individual DataFrames into a comprehensive dataset for both adult and kid products.
Data Cleaning: Removal of irrelevant columns and imputation of missing values.
Feature Extraction: Use of regular expressions to derive product strength (mg) from titles.
Data Aggregation: Calculation of average ratings per product for analysis.
Visualization: Plot the count of unique ASINs for each product category.
Descriptive Statistics: Summarization of the dataset post-cleaning to highlight key figures.
Files in the Repository
melatonin_analysis.ipynb: The Jupyter notebook with the analysis code.
CSV files: The datasets for each melatonin product subject to analysis.


### Dependencies
pandas: For data manipulation and analysis.
numpy: For numerical operations.
matplotlib: For creating static, interactive, and animated visualizations.
seaborn: For data visualization based on matplotlib.



### Usage
Install the required Python libraries mentioned in the Dependencies section.
Open the melatonin_analysis.ipynb file in a compatible IDE like JupyterLab or VSCode.
Run the cells in sequence to perform the analysis.
Insights Gained
Determined the count of unique products and their average customer ratings.
Uncovered the lowest average rating associated with each product title.
Charted the total number of reviews per year to assess customer interaction trends.
### Future Work
Broaden the scope of analysis to encompass more e-commerce platforms for a wider market analysis.
Implement sentiment analysis to understand customer emotions within review texts.
Contact Information
For inquiries about this analysis, please contact Deshpande.shr@northeastern.edu.
