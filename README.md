# Market_Analysis-for-Customer_Segnemtation

## Problem Statment
Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments.

For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

### Goal : Peform clustering to summarize customer segments to market them with relevant products.

## Column Description
People

-ID: Customer's unique identifier
-Year_Birth: Customer's birth year
-Education: Customer's education level
-Marital_Status: Customer's marital status
-Income: Customer's yearly household income
-Kidhome: Number of children in customer's household
-Teenhome: Number of teenagers in customer's household
-Dt_Customer: Date of customer's enrollment with the company
-Recency: Number of days since customer's last purchase
-Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products

-MntWines: Amount spent on wine in last 2 years
-MntFruits: Amount spent on fruits in last 2 years
-MntMeatProducts: Amount spent on meat in last 2 years
-MntFishProducts: Amount spent on fish in last 2 years
-MntSweetProducts: Amount spent on sweets in last 2 years
-MntGoldProds: Amount spent on gold in last 2 years

Promotion

-NumDealsPurchases: Number of purchases made with a discount
-AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
-AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
-AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
-AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
-AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
-Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

Place

-NumWebPurchases: Number of purchases made through the company’s website
-NumCatalogPurchases: Number of purchases made using a catalogue
-NumStorePurchases: Number of purchases made directly in stores
-NumWebVisitsMonth: Number of visits to company’s website in the last month

## Observations
*The optimal number of clusters is 4.
![image](https://github.com/Srijita2002/Market_Analysis-for-Customer_Segnemtation/assets/111299389/66980a06-e4ff-4e3e-96d5-dae68513a350)

#### Cluster 0

*The most crowded segment (963 customers).
*Middle income
*Mostly parents
*Low spending
*Relatively new customers for company
*Primary target audience for deals

#### Cluster 1

*Includes 490 customers
*Relatively older than cluster 0 and 2.
*Not a parent (at the max 2 members in the house)
*Top spending segment
*Highest income
*Habit of shopping from both web and catalog
*Relatively new customers for company
*Target audience for online campaings

#### Cluster 2

*Smallest group (150 customers)
*Lowest income
*Not a parent (at max 2 members in the house)
*Low spending
*Secondary target audience for deals

#### Cluster 3

*Second most populous segment (609 customers)
*Mostly parents
*Relatively older than other segments
*Loyal customers for the company
*Habit of shopping from web
*High income
*High spending
*Primary target audience for online campaigns

