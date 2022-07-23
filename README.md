# GROCERY-SALES-PROJECTIONS 
## PREDICTING SALES VOLUME AT VARIOUS STORES
#### Jonathan Jones 
#### 22.04.29
#### This project aims to help the retailer understand the properties of their products and outlets that play a key role in predicting sales.

## DATA
#### This data set encompasses various features associated with revenue including, but not limited to, the type and quantity of items sold, the type, size, and location of the outlets or stores that the items are sold to, the maximum retail price of each item, and the individual outlet sales for each item. It is important to separate, regroup and isolate these elements so that they can collated, correlated and analyzed against current sales. The insights from the evaluation can then be used to determine a strategy for revenue growth. 
![image](https://user-images.githubusercontent.com/101145586/165904456-898edc65-da05-48b7-b8ba-19b3d84e1cdb.png)

## VISUAL ANALYSIS

Once the data is processed and free of duplicates, missing, values and other anomalies it can be used for visual analysis. Graphs and heatmaps are used to organize, and simply huge quantities of data and illuminate trends. 

![image](https://user-images.githubusercontent.com/101145586/165904154-6b500726-3d61-4a57-8678-b0e4883075f1.png)

When comparing the Item Type Counts with Item Type by Store Sales we can readily see that the average sales per item are similar despite vast differences in item quantity. A focus on the sale of specific items, particularly items with higher retail prices, may be a good place to concentrate resources.

![image](https://user-images.githubusercontent.com/101145586/165905110-a09f4994-d971-4fa7-9a8d-07f43530dfaa.png)

Heat maps can help with concentrating our focus on elements that share a relationship. They can also be used to affirm our initial insights; there is significant positive correlation between Max Retail Price and Item Outlet sales. 

## MACHINE LEARNING & MODELING

Machine learning is used to streamline, expedite and enhance the forecasting process by removing repetitive manual procedures. Automating algorithms or programs allow for higher efficiency, deeper insights, and higher profitability. 
In the Machine Learning section, we use a copy of the unadulterated data as a basis and instructive training tool for our models. Two different models are used with this training data to draw inferences and detail elemental relationships between features or columns so that they will be able to interact with, and perform similar analysis on testing or unseen data. 

## INSIGHTS & EVALUATION

Both the Linear Regression and Regression Tree models exhibit high bias or underfitting, meaning that they have difficulty formulating predictions on training and testing data regardless of which featrues are used from the current matrix. Their respective test and training scores are close in value but ultimately too low to inspire confidence in their performance. 

## BUSINESS RECOMMENDATIONS

I would recommend the Regression Tree model over the Linear Regression model even though the difference in their performance, as measured by Coefficient of Determination or R2, is slight. However, I would ask the stakeholders to prioritize the production and collection of more data for either models training. Both models performed poorly, and I believe that the main issue is the lack of data and/or the quantity and types of features used to predict future values for our target, Item Outlet Sales.

## SUMMARY

Observation:
It is evident from the correlation matrix and model test scores that there are few features that are positively correlated with our target. After Item Maximum Retail Price, with a positive correlation value of 0.57, the strongest correlation with our target is Item weight with a value of 0.012 – this is an insignificant correlation. Without 3 or more strongly correlated features the performance of most models would be in question. Several of the columns provided in the dataset are inherently ineffective in efforts to predict sales outcomes. Item Identifier, Outlet Identifier and Outlet Establishment Year are such columns. 

Proposed Solution: 
I would suggest that the stakeholders explore metrics related to foot traffic, neighboring/anchor tenants, and demographical metrics (populations size, average age, marital status, number of children, education level, income, occupation, etc.). These metrics would help the models and stakeholders learn more about the habits and preferences of their local customers. The addition of these new features in conjunction with more data for the current feature columns would drastically improve the complexity, and predictive capacity of the current models, laying the foundation for definitive decision making and confidence capital re-allocation. 

## REFERENCES
#### https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
#### https://www.codingdojo.com/los-angeles
