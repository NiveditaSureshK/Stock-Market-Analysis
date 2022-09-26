# Stock-Market-Analysis

## Problem Statement
The following factors need to be examined in order to conduct an analysis:
1. Closing Price of Stocks & Volume Trading
2. Daily Returns
3. The year with the highest closing price
4. Relationship between companies in terms of closing price
5. Assess the risk by identifying the most common range of data points

## Dataset

The dataset for this project can be downloaded here: https://bit.ly/SandP500StockData

- Overview of features in the dataset

   <img width="332" alt="Dataset overview" src="https://user-images.githubusercontent.com/71536311/192172474-fb920796-6b0e-4526-852e-6b364569d1ae.png">

- The dataset has the following columns:
    - **Date** - in format: yy-mm-dd
    - **Open** - price of the stock at market open (this is NYSE data so all in USD)
    - **High** - highest price reached in the day
    - **Low Close** - lowest price reached in the day
    - **Volume** - number of shares traded
    - **Name** - the stock's ticker name

## Data Analysis



## Tools Used
Jupyter Notebook is used as IDE.
Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
Geopy and Folium libraies were used to perform Spatial Analysis.
GitHub is used as version control system


🎉 Tasks performed under Spatial Analysis:
Extract the "Latitude" and "Longitude" w.r.t. different Locations using Python's Geopy Library.
Generated a "BaseMap" of Bangalore using Python's Folium Library.
Plotted a HeatMap based of variety of Use Cases with the help of Python's Folium "HeatMap" Plugins.
Performed "Marker Cluster Analysis" on top of the "HeatMap" using Python's Folium "FastMarkerCluster" Plugins.
🌱 Some Exciting Glimpse of the Visuals:
Glimpse 1 Final Glimpse 2 Final Glimpse 3

 

For more details, please go through the Jupyter Notebook attached above.


## Conclusions
"Cafe Coffee Day" is on Peak. Next, We have "Onesta", followed by "Empire Restaurant" and so on.
"64.4%" Restaurants accepts Online Order whereas around "35.6%" Restaurants does not accepts Online Order.
Highest Voted Restaurant is "Onesta", followed by "Truffles" and "Empire Restaurant".
Widefield and BTM has the Maximum Number of Restaurants.
Most of the Highest Rated Restaurants Accepts "Online Order" and they are, of course, affordable whereas there are some Highest Rated Restaurants who do not Accepts "Online Order" and they are Expensive.
Average number of Votes for both Categories Varies because the Restaurant who's Accepting "Online Orders", get More "Votes" from Customers as there is a "Rating" window popping-up after each 'Order Place' from the "Zomato" Application. That's Why Restaurants having 'Online Order' faciliy has "Maximum Number of Votes" compared to do not ones.
More than 50% of Restaurants having approximate cost for 2 people is less than "1000 Rs." and they are Affordable too in Bangalore.
Around "372" Restaurants are "Affordable" as well as they have good "Rating" I.e. greater than 4 out of 5.
"BTM", "5th Block", and "HSR" has the Most Number of Restaurants/Most Foodie Areas. "BTM" dominates the section by having around "5K" Restaurants.
In "South-East" Bangalore Region, We have "Maximum Number of North Indian Restaurants". Again in that Zone, We might have a "Maximum Number of North Indian People".
In "South-West" Bangalore Region, We have "Maximum Number of "South Indian Restaurants" followed by "Central" and "South-East" Bangalore.
Now, In terms of "Biryani", in "South" Bangalore Region, We have "Maximum Number of "Biryani cuisines Restaurants" followed by "South-West" and "Central" Bangalore.
And so many more!!
