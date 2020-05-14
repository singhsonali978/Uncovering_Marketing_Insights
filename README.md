# **Uncovering Marketing Insights**


## **Dashboard of Salesforce**

Format: ![Alt Text](https://github.com/singhsonali978/Uncovering_Marketing_Insights/blob/master/Dashboard.png)


# **About Datasets**
The online.csv file contains actual order data manually imported from the Google Store public access Google Analytics. This data can't be accessed via API, unfortunately.
The KEY_SKU.csv file is the link between stock codes and product skus the permit joining the files
The Marketing_Spend.csv file is a fake file containing marketing budgets for online and offline advertising. It was created to practice building a model predicting sales from the marketing budget

# **Different concepts of marketing we have implemented**
 

### Cohort Analysis
Cohort analysis in e commerce means to monitor your customers’ behavior based on common traits they share – the first product they bought, when they became customers, etc. – to find patterns and tailor marketing activities for the group.
 
Recency, Frequency and Monetary Value 
RFM is an acronym of recency, frequency and monetary. Recency is about when the last order of a customer. It means the number of days since a customer made the last purchase. If it’s a case for a website or an app, this could be interpreted as the last visit day or the last login time.
Frequency is about the number of purchases in a given period. It could be 3 months, 6 months or 1 year. So we can understand this value as for how often or how many customers used the product of a company. The bigger the value is, the more engaged the customers are. Could we say them as our VIP? Not necessary. Cause we also have to think about how much they actually paid for each purchase, which means monetary value.
Monetary is the total amount of money a customer spent in that given period. Therefore big spenders will be differentiated with other customers such as MVP or VIP.
T represents the age of the customer in whatever time units chosen (weekly, in the above dataset). This is equal to the duration between a customer’s first purchase and the end of the period under study.

### Lifetime Value

 The LTV is an important building block in campaign design and marketing mix management.   Although targeting models can help to identify the right customers to be targeted, LTV analysis can help to quantify the expected outcome of targeting in terms of revenues and proﬁts. The LTV is also important because other major metrics and decision thresholds can be derived from it. For example, the LTV is naturally an upper limit on the spending to acquire a customer, and the sum of the LTVs for all of the customers of a brand, known as the customer equity, is a major metric for business valuations. Similarly to many other problems of marketing analytics and algorithmic marketing, LTVmodeling can be approached from descriptive, predictive, and prescriptive perspectives.

Customer lifetime value can also be defined as the monetary value of a customer relationship, based on the present value of the projected future cash flows from the customer relationship.Customer lifetime value is an important concept in that it encourages firms to shift their focus from quarterly profits to the long-term health of their customer relationships. Customer lifetime value is an important metric because it represents an upper limit on spending to acquire new customers.For this reason it is an important element in calculating payback of advertising spent in marketing mix modeling.

### Demonstration of personalized coupons

Based of RFM analysis we have segmented the customer into Gold ,Silver and Bronze category.
How this segmentation can be used is demonstrated by generating personalized coupons for each customer in every segment.

First we find the favourite category of each customer  and based on their segment we generate coupons of 10, 20  or 30% discount on their next purchase.

## **Formulations we have used**

Average order value = Revenue / Transaction per customer

Profit Margin Profit margin is the commonly used profitability ratio. It represents how much percentage of total sales has earned as the gain.

Purchase Frequency is the average number of purchases made by a customer over a defined period of time (typically one month or one year). It is the sum of total number transactions divided by total number customers.

Repeat rate shows you the percentage of your current customer base that has come back to shop again.

Churn Rate is the annual percentage rate at which customers stop subscribing.

Customer lifetime value, lifetime customer value, or life-time value is a prediction of the net profit attributed to the entire future relationship with a customer.

## Running Jupyter Notebook
 1. Create a folder in your goole drive and store the provided datasets there. 
 2. In google collab on the run time tab click change runtime and then Hardware accelerator as GPU
 3. Update the path variable to the location where the datasets reside in your drive
 4. Jupyter notebook then should be run on Google Collab 
 
 All the visualiztion from Pandas, Xsvs Scripts and images , Trifacta, Salesforce are given in respected folder
