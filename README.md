# Walmart-Business-Case-using-CLT-and-confidence-Interval

## About Walmart
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

## Business Problem
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

## About the Dataset
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday.
- User_ID               :	User ID
- Product_ID            :	Product ID
- Gender                :	Sex of User
- Age                   :	Age in bins
- Occupation            :	Occupation(Masked)
- City_Category         :	Category of the City (A,B,C)
- StayInCurrentCityYears:	Number of years stay in current city
- Marital_Status        :	Marital Status
- ProductCategory       :	Product Category (Masked)
- Purchase              :	Purchase Amount

## Solution Approach
- Perfroming uniavariate, bivariate and multivariate analysis, looking for outliers and missing values.
- We will predict the population mean of average purchase done by both males and females using central limit theorem with varying confidence.
- We will also see the how the predicted population mean changes with varying confidence and varying sample sizes.
- We will predict the population mean of average purchase based on marital status using central limit theorem and observe how the predicted population mean changes with varying confidence and sample sizes.
