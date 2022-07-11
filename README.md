# ECommerce A/B Testing
# [![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](https://dpghazi.github.io/projects/ecommerce-ab-testing.html)

## Project Description
A company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. For this project, I will be working to understand the results of an A/B test run by an e-commerce website if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.   

### Overview
* Introduction
* Part I: Probability
* Part II: A/B Test
* Part III: Logistic Regression
* Conclusion

Before Part I: Probability, I will perform data cleaning such as checking missing data, discrepancies between the columns etc.

### Language & Package
This project is using Python. The packages are used in this project including Numpy, Panda, random, matplotlib.pyplot, scipy.stats, and  statsmodels.api.

### Metadata of variables
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

### Methodology
* A/B Test
* Two-Proportion z Test
* Logistic Regression

### Report
* [Notebook](https://dpghazi.github.io/projects/ecommerce-ab-testing.html)
