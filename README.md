Course project for "Artificial Intelligence and Management" of the Department of Business Administration at the National and Kapodistrian University of Athens.

# **Product Classification & Data Quality Analysis**

This project explores text classification using the Multinomial Naive Bayes algorithm. It focuses on a comparative study of two datasets to demonstrate how semantic correlation and data quality impact model accuracy—specifically moving from a 3.00% baseline to 62.68% accuracy.

**Project Overview**

- Exploratory Data Analysis (EDA): Statistical analysis of product metadata (Price, Stock, etc.) using pandas and matplotlib.

- Text Processing: Converting product descriptions into numerical features using TF-IDF Vectorization.

- Machine Learning: Implementing a Naive Bayes pipeline to categorize products (e.g., Beverages, Candy, Coffee).

- Performance Comparison: An analytical deep-dive into why certain datasets fail to provide enough "keyword strength" for effective machine learning.

**Prerequisites**

To run this project, you will need Python 3.x and Jupyter Notebook.

**Required Libraries**

You can install the necessary dependencies using pip:

Bash:
pip install pandas numpy matplotlib scikit-learn notebook
