# Zillow Data Analytics Project

![Project Image](https://m.media-amazon.com/images/I/71ax+BgCs5L.jpg)  

This project is an end-to-end analysis of housing data scraped from Zillow. The project is divided into two parts: web scraping, data processing and model building.

## Part 1: Data Scraping

In this phase, housing data is scraped from Zillow using BeautifulSoup and Python. This includes details such as Zestimate, number of bedrooms, bathrooms, square footage, and other relevant information for each listing.

[View the Notebook for Part 1](https://github.com/mudit-mishra8/Zillow/blob/main/WebScrapping.ipynb)

## Part 2: Data Cleaning, Transformation, Feature Engineering, and Model Building

In this section, the scraped data is cleaned, transformed, and prepared for model building. This includes handling missing values, vectorization, and feature engineering. A Linear Regression model is built to predict the Zestimate of a property.

[View the Notebook for Part 2](https://github.com/mudit-mishra8/Zillow/blob/main/Zillow%20Zestimate.ipynb)

## Technologies Used
- Python
- BeautifulSoup
- Scikit-Learn
- Pandas
- Numpy

## Conclusion

This project demonstrates the complete process from collecting data through web scraping, preparing it for analysis, building a predictive model.We have found that the linear regression model was not good enough to capture the relationship.But still we found some significant p values associated with certain independent variables. Hence,we can not use linear regression for the prediction as it was found that the relationship between the set of independent variables and dependent variables is not linear.
