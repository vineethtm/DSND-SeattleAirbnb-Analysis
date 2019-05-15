# Project Description
----
### Introduction

Airbnb is an online marketplace primarily for homestays. Home owners can list their propery on Airbnb. Owners decide the price and Airbnb is profitted by charging an additional fee over price

In the analysis, I'm interested in few questions

1. What is the impact of features of a listings on its price ? Can we predict the price ?
2. How does price and availability changes ?\
   For a regular hotel room, price changes based on the season or days of a week. Is this true for a Airbnb 
   home ? Most of the hotel rooms are available throughout the year ? Do Airbnb homes follow the same pattern ?
   What is the impact of features of a listings on its price ?
3. What do we know about the reviews ?\
   Reviews are very important for hotel rooms. How often Airbnb room get reviews ? Are they Authentic ?

## Data
Data is downloaded from \
https://www.kaggle.com/airbnb/seattle/data \
It corresponds seattle airbnb data of 2016

The data consists three tables
1. lisings.csv\
Describe different features of the homes
2. calendar.csv\
Describe the availabilty and prices for each day  of 2016
3. reviews.csv\
It comprises the reviews received by a listing

## Techniques used

Data preprocessing\
Data Visualisation- (barplots,boxplots,line plots,heatmaps)\
Linear Regression\
Natural Language Processing

## Libraries Used
Pandas, numpy, sklearn, seaborn, matplotlib. wordCloud, statsmodels,nltk

## Summary
Model built using the features of the listings does a good job in predicting the prices. A Number of features that are highly correlated with the prices are identified. They are listed below
<br>
1. accommodates
2. bathrooms
3. bedrooms
4. various review scores
5. room type
6. neighbourhood
<br>

The median prices is 100$. Mid quartile range is from 75 to 150. Price changes with the neighbourhood. But it is possible to find budget rooms in every neighbourhood

Similar to prices, number & type of listings varies with the neighbourhood. Apartments are popular in few locations while houses are popular in other locations

Both monthly average price and total monthly availability shows seasonal changes. Prices are highest in July and lowest in January  while availability is highest December and lowest in January. However for most of the listings prices do not change throughout the year.

On average, people write only one review and median number of reviews received by listings is 13. Reviews seem authentic. The instances were a reviewer has given more than one review to a listing is not high
