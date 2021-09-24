# 🛒🧍 CLIENT BEHAVIOR STUDY - CLUSTERS 
___
## 🔍 PROBLEM AND PRODUCT

In this projetct I used the Kaggle dataset locate in this link:<br> https://www.kaggle.com/imakash3011/customer-personality-analysis

In this project I intend to segment the grouping of customers using the K-Means algorithm and then I will analyze the groups. This will help the marketing department better understand their customers and classify them to plan personalized marketing campaigns for each group.<br>
Another purpose is to send a link to the marketing team with the grouped data.

The final product will be something similar to this:

![image](https://user-images.githubusercontent.com/46419374/134188663-824b29d2-0ddb-42ad-b297-7ba6f33f5fb7.png)


___
## 📑  PROJECT ORGANIZATION 

The project is organized following the subtopics below:

- **Data Treatment:**<br>
  We verify if that is any missing data, and create some atributes to help our analysis
  
- **Descriptive Analysis:**<br>
  We give an overview analysis of the data in order to better understand the client behavior.
  
- **Insights:** <br>
  In this topic we take some insights of the clients behavior in order to give to other teams.
  
- **Data Pre-processing:**<br>
  This part we pre-processing the data to apply on our Machine Learning Model.
  
- **Elbow Method:**<br>
  We'll use this method to define the number of clusters in order to give the best perfomance to our algorithms.
  
- **Cluster Models: K-Means**<br>
  We'll apply the K-Means model and analyse the grouped data.
___
## 📑  FINAL PRODUCT

After we apply the previous steps we'll deliver a table containing the clustering data and a graphic containing the proportions of each groups, resulting in the table and graphic below

**Final Dataset:**
![image](https://user-images.githubusercontent.com/46419374/134181565-78e971da-9739-451b-91ea-2763875da858.png)

**Final Graphic:**
![image](https://user-images.githubusercontent.com/46419374/134181952-1f049024-3367-468f-b462-eeef6627d6cc.png)

**Link to the cluster data***
https://customer-behavior-cluster.herokuapp.com/

___
## 📑  PROJECT ATRIBUTES

***People***

- **ID:** Customer's unique identifier
- **Year_Birth:** Customer's birth year
- **Education:** Customer's education level
- **Marital_Status:** Customer's marital status
- **Income:** Customer's yearly household income
- **Kidhome:** Number of children in customer's household
- **Teenhome:** Number of teenagers in customer's household
- **Dt_Customer:** Date of customer's enrollment with the company
- **Recency:** Number of days since customer's last purchase
- **Complain:** 1 if customer complained in the last 2 years, 0 otherwise

***Products***

- **MntWines:** Amount spent on wine in last 2 years
- **MntFruits:** Amount spent on fruits in last 2 years
- **MntMeatProducts:** Amount spent on meat in last 2 years
- **MntFishProducts:** Amount spent on fish in last 2 years
- **MntSweetProducts:** Amount spent on sweets in last 2 years
- **MntGoldProds:** Amount spent on gold in last 2 years

***Promotion***

- **NumDealsPurchases:** Number of purchases made with a discount
- **AcceptedCmp1:** 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- **AcceptedCmp2:** 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- **AcceptedCmp3:** 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- **AcceptedCmp4:** 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- **AcceptedCmp5:** 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- **Response:** 1 if customer accepted the offer in the last campaign, 0 otherwise

***Place***

- **NumWebPurchases:** Number of purchases made through the company’s web site
- **NumCatalogPurchases:** Number of purchases made using a catalogue
- **NumStorePurchases:** Number of purchases made directly in stores
- **NumWebVisitsMonth:** Number of visits to company’s web site in the last month
