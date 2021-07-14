# Deepdive into Boston and Airbnb Data

Link to Access complete analysis : https://medium.com/@sam11.exultant/why-airbnb-homes-prices-differ-seattle-vs-boston-6a251a9db0d

Comparative analysis on how prices vary for Boston and Seattle cities

1. **Business Understanding** Airbnb is in property rental business, we want to do a comparative analysis for Boston and Seattle Market differ in various aspects and following are the important question to answer
- Q1 Is there any significant difference between Seattle and Boston AirBnB Homes.
-    A.How Prices in these Markets are vary in terms of Property Type , Room Type , Long Stay Property vs Short Stay Property
-    B.How seasonality is impacting Pricing and Inventory Availability for both cities
-    C.Do High Value Amenities varies for both the cities
- Q2 Which are the neighbourhoods which are getting high reviews but there is shortage of inventory leading to increase in price.
- Q3 What are the Key Features that are impacting rental pricing prediction for these cities ? Are these features vary between cities

2.**Data Understanding**  Data was fetched from http://insideairbnb.com/get-the-data.html. Boston dataset consists of 3146 listings while Seattle's has 4213 listings. Datasets were investigated before any preprocessing.

3.**Prepare Data** Following Techniques are used :

- Cleaning Dataframe
- Removing NaN
- Outlier Removal

4.**Data Modeling** Linear Regression model is used for seperatly for boston and seattle

5.**Evaluate the Results** Result and discussion are published in https://medium.com/@sam11.exultant/why-airbnb-homes-prices-differ-seattle-vs-boston-6a251a9db0d
