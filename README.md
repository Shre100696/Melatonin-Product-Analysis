# Melatonin-Product-Analysis


Introduction
This repository contains the analysis of various melatonin products sold on an e-commerce platform. The data spans several products, focusing on customer reviews, ratings, and product details. The analysis aims to uncover insights into product popularity, customer satisfaction, and potential areas for data quality improvement.

Dataset
The dataset includes several CSV files, each representing different melatonin products identified by their unique ASINs. The data was collated from multiple sources and loaded into pandas DataFrames for processing and analysis.

Analysis Overview
The code performs the following operations:

Loads data from CSV files into pandas DataFrames.
Conducts initial data exploration, such as checking the number of rows and columns and viewing the head of the DataFrames.
Assesses data quality by checking for missing values across the datasets.
Visualizes missing data distribution using seaborn's displot.
Concatenates individual DataFrames into a single dataset for adults and kids.
Cleans the data by dropping unnecessary columns and handling missing values.
Extracts product strengths (in mg) from product titles using regular expressions.
Aggregates data to analyze the distribution of average ratings per product.
Visualizes the number of unique ASINs per product type.
Describes the cleaned dataset to summarize key statistics.
Files in the Repository
melatonin_analysis.ipynb: Jupyter notebook containing the analysis code.
CSV files: Data files for each product analyzed.
Dependencies
pandas
numpy
matplotlib
seaborn
Usage
To run this analysis, ensure that you have the above-listed Python libraries installed. Load the Jupyter notebook in an environment that supports .ipynb files, such as JupyterLab or VSCode, and execute the cells sequentially.

Insights
The analysis revealed the number of unique products and their respective customer ratings.
Identified the minimum average rating for each product title.
Visualized the total reviews per year, indicating customer engagement over time.
Future Work
Expand the analysis to include additional e-commerce platforms for a comprehensive market view.
Integrate sentiment analysis to gauge customer sentiment from review text data.
Contact Information
For any further queries regarding this analysis, please reach out to Deshpande.shr@northeastern.edu.

