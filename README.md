# Laptop_sales_analytics-EDA


INTRODUCTION

This laptop dataset contains detailed information about 1,303 laptops, including specifications such as brand, type, screen size, resolution, CPU, RAM and price etc.

It offers a valuable opportunity to explore trends in laptop configurations and pricing. The data can be used to analyze how various features influence price and identify popular configurations across brands.

With some columns having missing values, preprocessing is essential before analysis. Potential objectives include studying market trends, or identifying key specifications that affect consumer preferences. This dataset provides rich insights for machine learning and data-driven decision-making projects.


AIM

The aim of this project is to analyze the laptop dataset to understand the relationship between various specifications (e.g., brand, CPU, RAM, screen resolution) and their impact on price. 

By uncovering trends and insights, this analysis can help consumers make informed purchasing decisions and provide manufacturers with valuable market intelligence


Handling missing values 

The method of dealing with missing values by filling numerical columns with the median and categorical columns with the mode is referred to as Imputation.

Median Imputation: For numerical columns, replacing missing values with the median is a robust method as it is not affected by outliers.

Mode Imputation: For categorical columns, replacing missing values with the mode ensures the most frequent category is used.

This combined approach is often referred to as Median-Mode Imputation or Simple Imputation in data preprocessing.


Outlier detection 

Outliers are detected by IQR method

Q1=25th percentile of the data
Q3=75th percentile of the data
Lower Bound=  Q1− 1.5 × IQR

                               Upper Bound=  Q3 + 1.5 × IQR


                                 IQR = Q3 – Q1




