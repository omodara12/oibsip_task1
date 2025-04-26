# EDA on Superstore dataset
## Introduction
##### This report presents insights derived from an exploratory data analysis (EDA) of Superstore sales data. The goal is to identify trends, patterns, and areas of opportunity to inform business decisions across sales, shipping, and profitability.
###### The dataset was gotten from [Kaggle](https://kaggle.com/datasets)

## Data Loading and Exploration
The data was loaded into Jupyter notebook

![data view](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/data%20eploration.png)

```python
df.shape
```
![shape](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/data%20shape.png)
[data shape](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/data%20shape.png)
###### The dataset contains 21 columns and 9994 rows

## Data Cleaning
##### I checked the data for missing values
```python
# # Check for missing values
print(" Missing values:\n", df.isnull().sum())
```

![missing values](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/missing%20values.png)
[missing values](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/missing%20values.png)

###### The data does not contain missing values

##### I also checked for duplicate values
``` python
# Check for duplicates
print("\n Duplicate rows:", df.duplicated().sum())
```

![duplicates values](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/duplicates.png)
[duplicates](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/duplicates.png)

###### The data does not contain duplicate rows.

##### The Data types are in accordance, there is no need to change their formats:
![data types](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/data%20types.png)
[data types](https://github.com/omodara12/oibsip_task1/blob/main/assets/images/data%20types.png)


## Descriptive Statistics

## Time Series Analysis

## Data Visualization

## Recommendations
###### 1. Optimize Product Focus:
###### •	Expand Technology offerings—high revenue and high profit.
###### •	Reassess furniture pricing, especially Tables and Bookcases—loss-making despite decent sales.
##### 2. Targeted Regional Strategy:
###### •	Invest in the South region with localized promotions and improved logistics.
###### •	Use data-driven campaigns to boost underperforming regions.
##### 3. Improve Shipping Efficiency:
###### •	Analyze delivery times and optimize routes for First Class and Same Day shipping, which underperform in cost-effectiveness.
##### 4. Refine Discount Strategy:
###### •	Discounts significantly affect profit margins—introduce threshold-based promotions that protect profitability.
##### 5. Customer Segmentation:
###### •	Engage Corporate customers with bundled offerings and loyalty programs.
###### •	Grow the Home Office segment with targeted online campaigns and personalized recommendations.

## Conclusion
##### This analysis revealed vital insights into Superstore’s sales dynamics. By focusing on high-performing categories, addressing low-profit segments, and refining regional and shipping strategies, the business can drive better profitability and customer satisfaction.
###### The dashboard offers a real-time view of performance, enabling continuous monitoring and smarter decision-making.


