# JaguarGroup_DTI_01_FinalProject🐈‍⬛
***
# Business Understanding
Olist is an e-commerce platform that connects sellers with buyers across Brazil. In a highly competitive market, understanding customers deeply is key to increasing their retention and loyalty. With increasing competition, Olist needs to develop a more targeted marketing strategy, based on customer behavior and characteristics. Customer segmentation using clustering models can assist Olist in identifying customer groups with different characteristics, enabling the implementation of marketing strategies tailored to the needs and preferences of each segment.
***
# Business Problem
Today, Olist faces the challenge of understanding the diversity of customer behavior. Without proper segmentation, marketing efforts are less effective because not all customers respond the same way to the same strategies. 
all customers respond in the same way to the same strategies. This 
can lead to low customer retention rates, and reduced revenue gain. 
Olists need to develop more personalized and relevant marketing strategies, 
that are based on a deep understanding of every segmented of customers.
***
# Objectives
The main objectives of this project are: 
- Analyze and understand the characteristics of Olist customers through the LRFM approach. 
LRFM (Length, Recency, Frequency, Monetary) approach. 
- Identify customer segments based on their shopping behavior.
using clustering technique. 
- Develop a segmented marketing strategy that is tailored to the characteristics of each customer segment. 
characteristics of each customer segment to increase retention, loyalty, and revenue. 
revenue.
***
# Analytical Approach
o Achieve this objective, the following analytical approach will be applied: 
## 1. Data Collection & Preparation: 
o Collect and clean data from the Brazilian E-Commerce Public
Dataset related to customers, transactions, and shopping behavior. 
o Calculate the LRFM (Length, Recency, Frequency, Monetary) values for 
each customer. 
## 2. LRFM Analysis: 
o Measures four main dimensions of customer behavior: 
▪ Length: The duration of the customer's relationship with Olist. 
Recency: Time since last purchase. 
Frequency: Number of transactions made by the customer. 
▪ Monetary: The total spending of the customer. 
## 3. Clustering: 
o Using clustering techniques (such as K-Means, DBSCAN, or 
Hierarchical Clustering) to group customers into segments based on their LRFM scores.
segments based on their LRFM values. 
o Determine the optimal number of clusters and validate the clustering results. 
## 4. Segment Analysis & Strategy Development: 
o Analyze each segment to understand their unique characteristics and needs. 
their unique characteristics and needs. 
o Develop different marketing strategies for each segment, 
such as special offers, loyalty programs, or retargeting campaigns.
With this approach, Olist is expected to reach out to customers with relevant and personalized strategies, which is expected to increase loyalty.
***
# Stakeholder
Marketing Team
***
# Segmented Customer
![See Plot](https://raw.githubusercontent.com/PurwadhikaDev/JaguarGroup_DTI_01_FinalProject/main/Assets/LRFM%20Distribution%20Area%20Chart.png)
- Cluster 0: **New Customers**
- Cluster 1: **Hibernating Customers**
- Cluster 2: **Champion**
- Cluster 3: **Potential Loyalist**

| Cluster | Customer_Total | Length_Range | Recency_Range | Frequency_Range | Monetary_Range      |
|---------|----------------|--------------|---------------|-----------------|---------------------|
| 0       | 50523          | 0 - 549      | 0 - 308       | 1 - 5           | 9.59 - 365.38       |
| 1       | 37483          | 308 - 772    | 53 - 772      | 1 - 6           | 10.07 - 406.92      |
| 2       | 849            | 41 - 742     | 41 - 742      | 1 - 5           | 1196.78 - 13664.08  |
| 3       | 7238           | 34 - 743     | 0 - 743       | 1 - 17          | 327.39 - 1195.23    |

***
# Data Overview
[Tableau Dashboard](https://public.tableau.com/views/OlistE-commerceDashboard_17245810079510/ProductSalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


