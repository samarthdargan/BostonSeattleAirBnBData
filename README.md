# Deepdive into Boston and Airbnb Data

Link to Access complete analysis : https://medium.com/@sam11.exultant/why-airbnb-homes-prices-differ-seattle-vs-boston-6a251a9db0d

**Motivation** : For this project, We want to explore the Boston and Seattle Airbnb dataset and find out the answer for below business questions

**Installation**
This project requires Python 3.7 and the following Python libraries installed:
1. Pandas
2. Numpy
3. MatPlotLib
4. SciKitLearn

**File Descriptions**
For each city, the dataset is composed of two CSV files:

- listings (1).csv.gz -â all detailed informations about listings

- calendar.csv.gzâ -â availability and price information by day


**Comparative analysis on how prices vary for Boston and Seattle cities**

1. **Business Understanding** Airbnb is in property rental business, we want to do a comparative analysis for Boston and Seattle Market differ in various aspects and following are the important question to answer

1. Is there any significant difference between Seattle and Boston AirBnB Homes. 
    1. How Prices in these Markets are vary in terms of Property Type , Room Type , Long Stay Property vs Short Stay Property
2. How seasonality is impacting Pricing and Inventory Availability for both cities
3. Does Top Amenities that are available in high-value properties vary between cities
4.  Which  are the neighbourhoods which are getting high reviews but there is shortage of inventory leading to increase in price.
5. What are the Key Features that are impacting rental pricing prediction for these cities ?  Are these features vary between cities

2.**Data Understanding**  Data was fetched from http://insideairbnb.com/get-the-data.html. Boston dataset consists of 3146 listings while Seattle's has 4213 listings. Datasets were investigated before any preprocessing.

3.**Prepare Data** Following Techniques are used :

- Cleaning Dataframe
- Removing NaN
- Outlier Removal

4.**Data Modeling** Linear Regression model is used for seperatly for boston and seattle

5.**Evaluate the Results** Result and discussion are published in https://medium.com/@sam11.exultant/why-airbnb-homes-prices-differ-seattle-vs-boston-6a251a9db0d

## Results of the Analysis ##

1. Seattle has 3.9K properties, 37% more than Boston. But Avg price of the property in Boston is 10% higher than in Seattle.
2. For Seattle City Avg Price for an Entire Apartment and Hotel Room is similar, whereas for Boston City, their Entire home costs ~5% high price
3. August is Peak Season for Seattle where prices are high, whereas peak season for Boston is during holidays.

## Acknowledgement ##
Thanks a lot for InsideAirBnb for providing us data 
