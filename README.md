# Vrinda Store Market Analysis - Excel Project
#### Excel Dataset Download (google drive): https://bit.ly/3Ypatqu 

##### Annual Report of Vrinda Store - .png is added

First of all,
A thorough examination of sales data from numerous e-commerce sites, such as Amazon, Myntra, Flipkart, Ajio, Meesho, and others, is summarized in the "Vrinda Store Annual Report". This study attempts to offer meaningful insights about the success of Vrinda Store over a year in various product categories and sales channels through rigorous data cleaning, processing, and analysis in Excel.

Techniques:

Data collection: Collected sales information from the various e-commerce sites that Vrinda Store uses.

Data cleaning: To guarantee correctness and consistency, duplicates were eliminated, mistakes were fixed, and data formats were standardized.

Data processing: 
    In one of the sample questions, we were asked to find  a relation b/w Age and Gender -
    So, I decided to make 3 age group - Senior (Over 50), Adult (Over 30 but below 50), Teenager (Below 30)

####    1st instance of age is in E2, so I made a new column called it "Age Group"
    IF(E2 >= 50, "Senior", IF(E2 >= 30, "Adult", "Teenager"))
####    It returned Adult in F2, we applied it on the complete column.
### SImilar and more complex data processing methods were applied before the analysis.
Data analysis: Several pivot tables were used to assess the performance of various sales channels and product categories, as well as to examine sales patterns and identify top-performing products.

Data Visualization: Using Excel slicers, an interactive dashboard was created with dynamic filtering depending on sales channels, product category, and month.
To improve readability and comprehension of the analysis, significant metrics and trends were visually represented using charts, graphs, and tables.
Components of the dashboard:

Slicers: Users may easily navigate and filter data with the use of three slicers (Month, Category, and Sales Channels), which let them customize the analysis based on their requirements.

Visualizations: The dashboard offers a comprehensive picture of sales success with a variety of visualizations, such as pie charts, line charts, and bar graphs.

# Insights

- Women are more likely to buy compared to men (~65%)
- Maharashtra, Karnataka and Uttar Pradesh are the top 3 states (~35%)
- Adult age group (30-49 years) is max contributing (~50%)
- Amazon, Flipkart and Myntra channels are max contributing (~80%)

# Conclusions
Final Conclusions to improve Vrinda Store Sales:
- Target women customers of age group (30-49 yrs) living in Maharshtra, Karnataka and Uttar Pradesh by showing them ads/offers/coupons available in Amazon, Flipkart and Myntra.

#### Analysis Done