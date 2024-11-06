# Background :
In a highly competitive retail market, effective campaign strategies are essential for driving customer engagement, increasing sales, and enhancing brand loyalty. With the increasing diversity of shopping platforms and customer preferences, it is crucial to understand which channels and products generate the most engagement. This analysis aims to optimize marketing campaigns by examining customer behavior across different platforms and demographics to identify areas for improvement.

# Problem Statement :
Despite previous campaign efforts, engagement and acceptance rates vary significantly across customer segments and platforms. Key challenges include understanding which campaigns have the highest impact, identifying the most effective shopping platform, and determining how demographic factors like income and marital status influence campaign responses. Addressing these gaps can improve targeting and increase overall campaign effectiveness.

# Analysis Objectives:
Identify which campaign strategies have been most effective to replicate successful tactics.
Determine the most popular shopping platform to focus campaign efforts accordingly.
Analyze spending patterns by product category to prioritize promotions on high-demand items.
Understand customer demographics, such as income levels and marital status, to create more targeted and effective campaigns.

# Supermarket Customers Data Dictionary
- People
ID:Customer's unique identifier
Year_Birth: Customer's birth year
Education: Customer's education level
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
Complain: 1 if the customer complained in the last 2 years, 0 otherwise
Products

MntWines: Amount spent on wine in last 2 years
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntFishProducts: Amount spent on fish in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
MntGoldProds: Amount spent on gold in last 2 years
Promotion

NumDealsPurchases: Number of purchases made with a discount
AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise
Place

NumWebPurchases: Number of purchases made through the company’s website
NumCatalogPurchases: Number of purchases made using a catalog
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to the company’s website in the last mont
Z-score

Z_CostContact = menunjukkan biaya atau pengeluaran dalam bentuk Z-score, mengindikasikan seberapa besar pengeluaran dibandingkan dengan rata-rata biaya
Z_Revenue = menunjukkan pendapatan pelanggan dalam bentuk Z-score, mengindikasikan seberapa besar pendapatan tersebut dibandingkan dengan rata-rata.
additional :

age colomn
household
rfm score
