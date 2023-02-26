# **Applying Business Analytics for Enhancing Food Delivery App. Performance Using Tableau**


## **Business Background** 
    - <u>DEBI</u> is a <u>start-up food delivery application</u> that started operating.
    - <u>Users</u> can make <u>orders</u> via the application to get food from a variety of different cuisines <u>restaurants</u>. 
    - Generally, across all business, there is an <u>ultimate sought-after</u> goal which is <u>maximizing profits</u>. 
    - According to DEBI’s business model, its <u>main and direct source</u> of <u>profits</u> is a <u>commission</u> on the delivered orders. 
    - Like any other business, DEBI needs to maximize its profits. 
    

## **Business Objectives**
    - Specifically, DEBI needs to <u>increase the number of delivered orders to increase its profits</u>.
    - Generally, DEBI's <u>performance</u> needs to be <u>improved</u> from different <u>managerial perspectives</u>.


## **Questions** 
     1. Does the number of <u>monthly delivered orders meet our target</u>?
     2. What is the <u>regional performance</u> of our app?
     3. Which <u>cuisines</u> our App users prefer?
     4. What is our users' <u>ordering behaviour</u>?
     5. How do users <u>pay</u> for their orders?
     6. How do users <u>rate</u> the app? <u>Why</u>? How to <u>improve</u> the rating?


## **Analytics Solutions / Methodologies**
    - Building <u>tableau visualizations</u> to get insights into DEBI's business performance.
    - Providing business users and managments with data-driven business recommendation to enhance DEBI's business performance.


## **Data Sources**

- **About:** users have used DEBI app to enjoy food and drinks from their homes just by placing orders via the app from any desired restaurant. This dataset describes the delivered orders since DEBI started operating. It’s extracted from DEBI's transactional orders database.   

- **Data Collection**
   - Using a SQL query to extract data from DEBI’s data warehouse (DWH) in the form of a CSV file. (i.e. orders - Restaurants) in the form of a CSV file. 
   - Using a shape file (.shp) holding regions and their names. 

- **Data Dictionary:**

| Column Name | Description | Sample Value  |
|-------------|-------------|---------------|
| Order Id    | The order's unique Id  | 211216115328MQGI |
| Order Date | The date/time when the order made | 2021-12-16 08:53:00 |	
| Lat | Is the latitude of the place where the order delivered  | 24.8288108957754 |
| Long   | Is the longitude of the place where the order delivered  | 42.9209892937493	|
| Restaurant Id    | The restaurants unique identifiers  | sdv574voij |
| Restaurant Name | The restaurants name that are in the app | Willies |
| Cuisine | The cuisine of the ordered restaurant | Italian | 
| Payment Mode | The payment method by which the user paid for the order | Credit card or cash | 
| Region | The name of Saudi Arabia regions | Makkah | 
| Delivery Time Taken (mins) | The total time taken in terms of minutes to deliver the order | 26 | 
| Customer Rating-Delivery | Is how the user rate the order delivery | 4. (i.e. 4 stars) | 
| Geometry | Is the geometrical polygon corresponding for each region, it exists in a shape file ( .shp) | 
  


## **Final Results**

![3d RFM Clusters](https://github.com/Ayman947/Marketing-RFM-CLTV-Segmentation/blob/main/clusters-3d-rfm.PNG)


## **Recommendations Summary**
    - The <u>marketing team</u> may launch a campaign promoting our application in the form of <u>promo codes and discount vouchers</u> as an incentive for users to order make more orders in the <u>less active regions</u>.
    - The <u>public relations (PR) team</u> may deal with <u>restaurants of our users' preferred cuisines</u> to add more varieties  to our app users.
    - The <u>supply team</u> is highly recommended to make sure of <u>delivery men availability at rush hours</u> to meet our users' <u>demand and increase the fullfillment rate</u>.
    - The <u>finance team</u> is recommended to improve <u>credit payment facilities and security</u>.
    -  Both <u>finance and supply teams</u> have to implement a new strategy to <u>decrease the delivery time and increase users' rating</u>.

> Consequently, these recommendations  will help in increasing the <u>number of monthly delivered orders</u> to meet or even exceed the <u>100k monthly delivered orders target threshold</u>.
