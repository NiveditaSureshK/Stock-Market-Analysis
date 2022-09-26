# Stock-Market-Analysis

## Problem Statement
The following factors need to be examined in order to conduct an analysis:
1. Closing Price of Stocks 
2. Total volume of stocks being traded each day
3. Daily Returns
4. The year with the highest closing price
5. Relationship between companies in terms of closing price
6. Assess the risk by identifying the most common range of data points

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

#### Closing Price of Stocks
- Convert string to date format of the **‘date’** feature
- Extract all the names of the companies (Amazon, Apple, Google and Microsoft) and plot the graph using **pyplot** module of Python's ***matplotlib*** library

<p align="center"><img width="530" alt="image" src="https://user-images.githubusercontent.com/71536311/192176573-2ec7c7a9-d8f5-42a3-ac22-6dba3a90fb4e.png"></p> 

#### Total volume of stocks being traded each day
- Visualized volume trading using Python graphing library **plotly**

<p align="center"><img width="710" alt="image" src="https://user-images.githubusercontent.com/71536311/192260841-81bf6889-5f87-4aa1-82ad-3e2717a54335.png"></p> 
<p align="center"><img width="676" alt="image" src="https://user-images.githubusercontent.com/71536311/192274806-1975d653-dc4a-443e-8d17-a9bc8fae1192.png"></p> 

## Tools Used
Jupyter Notebook is used as IDE.
Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
For visualization of the plots, Matplotlib, Seaborn, Plotly are used.

For more details, please go through the Jupyter Notebook attached above.

