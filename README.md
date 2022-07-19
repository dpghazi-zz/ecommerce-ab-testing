# ECommerce A/B Testing

## Project Description
A company has developed a new web page in order to increase the number of users who "convert" (the number of users who decide to pay for the company's product). For this project, I performed A/B tests to analyze the changes (conversion rate of the shoppers) through statical conclusions; implement the new page, keep the old page, or perhaps run the experiment longer to make their decision. 

### Overview
* Preprocessing 
* Two-Proportion Z Test
* A/B Test
* Logistic Regression

### Language & Package
Python (Pandas, Numpy, Random, Matplotlib PyPlot, Scipy, Statsmodels API)

### Metadata of Variables
1. [ab_data.csv](https://github.com/dpghazi/ECommerce-AB-Testing/blob/main/ab_data.csv)  

| Variable Name | Metadata                   |
|---------------|----------------------------|
| user_id       | 6-digit numbers            |
| timestamp     | string                     |
| group         | string: control, treatment |
| landing_page  | string: old_page, new_page |
| converted     | numeric: 0:No, 1:Yes       |

2. [countries.csv](https://github.com/dpghazi/ECommerce-AB-Testing/blob/main/ab_data.csv)  

| Variable Name | Metadata           |
|---------------|--------------------|
| user_id       | 6-digit numbers    |
| country       | string: US, CA, UK |

### Featured Notebook
* [ECommerce A/B Testing](https://dpghazi.github.io/projects/ecommerce-ab-testing.html)
