# Airbnb Australia Price Analysis
Exploring pricing patterns, occupancy trends and the different key features that drive and influence Airbnb revenue across major Australia cities and states (Melbourne, Sydney, Brisbane, Tasmania and Western Australia).

## Overview
This project aims to use exploratory data analysis (EDA),  data visualisations and predictive modeling to uncover what makes an Airbnb listing successful in the Australian market. It attempts to answer several key questions such as: What drives listing price and revenue? What do guests actually care about? What are the key differences between Airbnb listings across different states in Australia?

## Key Findings
- Guests value accuracy, value and cleanliness above all else
- Number of reviews, price and location are the strongest predictors of revenue from our xGBoost model, while property characteristics such as bedrooms, bathrooms contribute significantly less
- Our XGBoost regression model is able to explain 67.6% of the variance in estimated revenue across listings

## Limitations
- Listing photos, descriptions or host responsiveness were missing from the dataset but may have been meaningful drivers of performance
- Seasonality is not accounted for in the dataset
- Estimated revenue is a modelled figure calculated by Inside Airbnb using listing price and estimated occupancy (as actual booking data is private to Airbnb). As such, findings around revenue should be interpreted as indicative rather than exact.

## Data
Inside Airbnb (June, 2025) - https://insideairbnb.com/get-the-data/
