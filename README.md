# PCAIML_practical_App1: Will the Customer Accept the Coupon

## Overview
The goal of this project is to distinguish between customers who accepted a driving coupon versus those that did not.

## Dataset
You can find the dataset used to make the analysis in this [path](../data/coupons.csv).

## Tools and libraries
Python programming language was used to read the dataset. libraries such as panda, seaborn, matplotliib for analysis and visualizing.
the details of the anaysis, comments and visualization charts can be found in the following [jupyter notebook](prompt.ipynb)

## Exploratary Data Analysis

### Missing data
A significant portion of the values in the car column are missing, rendering it uninformative for analysis. Therefore, We safely dropped the car column, as it holds little to no significance in the dataset.
On the other hand, columns such as coffeeHouse and CarryAway contain only a small number of missing values, which are negligible and unlikely to affect the overall integrity or outcomes of the analysis.

### Anaysis
![Alt visualization of coupon category](./images/coupon_column.png)

Since the first part of the project focused on the Bar coupon we also dropped the nan for Bar columns.


