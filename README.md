# Food-Sales-Predictions-
## Predicting sales volume at various stores
#### Jonathan Jones 
#### 22.04.29
### This project aims to help the retailer understand the properties of their products and outlets that play a key role in predicting sales.

## DATA
#### This data set encompasses various features associated with revenue including, but not limited to, the type and quantity of items sold, the type, size, and location of the outlets or stores that the items are sold to, the maximum retail price of each item, and the individual outlet sales for each item. It is important to separate, regroup and isolate these elements so that they can collated, correlated and analyzed against current sales. The insights from the evaluation can then be used to determine a strategy for revenue growth. 
![image](https://user-images.githubusercontent.com/101145586/165904456-898edc65-da05-48b7-b8ba-19b3d84e1cdb.png)


## DATA EXPLORATION & DATA CLEANING 

The following outlines the sequencing and methodology used for understanding and then cleaning or preparing the data for visual analysis
1.	We began by identifying and removing rows of duplicated data
2.	Next, we checked for missing values and made the decision to use two different imputation strategies based on the data type of the column that the missing value or NaN was in. 
a.	The most frequent observation was used to replace NaNs in object columns 
b.	The mean was used to replace NaNs in numeric columns
3.	After confirming that the missing values were eliminated, we employed a ‘for loop’ to identify all of the non-numeric columns so that we could check for inconsistencies amongst their values. 
a.	‘Low fat and ‘low Fat’ were consolidated for example as they both represent the same value type. 
4.	Lastly, we used a statistical summary to gain a better understanding of the values in the numeric columns. 


## VISUAL ANALYSIS

Now that the data is free of duplicates, missing values and other anomalies it can be used for visual analysis. Graphs and heatmaps are used to organize, and simply huge quantities of data and illuminate trends. 

![image](https://user-images.githubusercontent.com/101145586/165904154-6b500726-3d61-4a57-8678-b0e4883075f1.png)

When comparing the Item Type Counts with Item Type by Store Sales we can readily see that the average sales per item are similar despite vast differences in item quantity. A focus on the sale of specific items, particularly items with higher retail prices, may be a good place to concentrate resources.

![image](https://user-images.githubusercontent.com/101145586/165905110-a09f4994-d971-4fa7-9a8d-07f43530dfaa.png)

Heat maps can help with concentrating our focus on elements that share a relationship. They can also be used to affirm our initial insights; there is significant positive correlation between Max Retail Price and Item Outlet sales. 

## MACHINE LEARNING DATA PREPARATION & MODELING


## INSIGHTS & EVALUATION

## BUSINESS RECOMMENDATIONS

## SUMMARY

## REFERENCES
#### https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
#### https://www.codingdojo.com/los-angeles
