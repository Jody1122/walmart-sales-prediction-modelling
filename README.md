# Exploring Retail Dynamics of Walmart Weekly Sales Drivers

## Introduction

Walmart has been a driving force in the retail sector, standing out as the largest private employer and the world’s largest retailer because of her innovations in supply chain management, pricing strategies and improving customer experience. Working on a subset of the many outlets in several countries of the world, I seek to understand the factors or combination of factors that affect sales outcome. To give a comparative understanding of store performance, our study focuses on breaking down the impacts of internal and external factors on sales outcomes on selected Walmart stores.

## Objectives

The objective of this study is to carry out a Multiple Linear Regression modelling to predict the factors that impact Walmart weekly sales and identify correlations and interactions which have the most effect based on available data and finally choose the best predictive model. The variables of interest include:

* Weekly_sales ($) - sales for the given department in the given store. 
* Temperature (F) - average temperature in the region. 
* Fuel_Price - cost of fuel in the region. 
* CPI - (Consumer Price Index) measure of changes in retail prices over time for standard goods and services
* Unemployment - the unemployment rates each week. 
* IsHoliday - whether the week is a special holiday week. 
* Size - floor area (SQF)

## Methods

Firstly, I performed data cleaning and wrangling to ensure the dataset is fit for analysis, dealing with missing values, outliers and handling irrelevant columns.Next, I applied Multilinear Regression analysis to uncover the relationships between the dependent variable; Walmart's Weekly sales and other independent variables listed above is carried out.   Starting with the full additive model, removed insignificant variables, examined all regression analysis, tested interactions terms, perform partial f-test.

Secondly, I conducted assumption checks. Assumption checks were carried out on the best-fit model as follows:
* Linearity Assumption
* Normality Assumption (Histogram, Q-Q plot Shapiro-Wilk Test)
* Equal Variance Assumption
* Multi-collinearity
* Outlier Analysis (Cook’s distance and leverage)

Lastly, I performed Experimental Design to test whether the Store classification & holidays' effects had impacts on Walmart Weekly sales.

## Tech stacks
* R


## License

This project is licensed under the MIT License.

## References
1. The Kaggle (2024, February 15). "Walmart Sales " Retrieved from https://kaggle.com/datasets/mikhail1681/walmart-sales?resource=download Date accessed: 2024, March 01.

2. The Kaggle (2014). "Walmart Recruiting - Store Sales Forecasting" Retrieved from https://kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data?select=stores.csv Date accessed: 2024, March 01. 