# Project 2 - Ames Housing Data and Kaggle Challenge

# Predictng Home Sale Prices: Training the Trend


Accurate Pricing of a home for sale is essential to any real estate agency. When listed price is too high, it can deter potential buyers whereas the opposite will result in loss of income for sellers as well as reduced commission for the realtors. There needs to be the right balance of listing price for your listing to be sold quickly in the amount it is listed for. 


To answer this challenge, I have developed a data-driven regression model using the Ames housing dataset to predict house sale prices with high accuracy and find the top variable that tends to bring the change. This will guide local real estate agencies to work with the sellers in establishing data-backed selling price. This model could also benefit potential homebuyers in putting their offers for houses in the market. 


# Data Dictionary
https://www.kaggle.com/competitions/dsb-210-regression-challenge/data

All the data is taken from kaggle dataset listed above. The data page consists of full details of all 81 columns and the entries in them. 

# Executive Summary

This project aims to explore the relationships between various variables present in order to build a model that accurately predicts the Sale Prices.The steps involve Exploratory data analysis and building the model in order to help answer the data science problem.

# Methodology

I used various methods for EDA to check the correlation of the variables. Missing values were imputed with mean, median or with 0 according to the data dictionary. I checked for outliers and columns that were mostly empty and removed them as I saw fit. I created dummy variable for the garage type column which I used in building my models. I then created couple of models comparing root mean squared error and the r2 values of each models. 

# Conclusion
My best performing value has R²is 90% i.e. 90% of variance in the Sale Price is explained by my model's input.
My Training RMSE is 24334.03 i.e. My model's predictions are off by $24334.03 on average.
My coefficient for overall quality is 0.084117, which means my sale price increases by 8.4%, for each increase in overall quality points.
Recommendation:
- When pricing a home, the overall quality of the home must be taken into great consideration.




