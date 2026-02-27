# Airbnb Australia Price Analysis
Exploring pricing patterns, occupancy trends and the different key features that drive and influence Airbnb performance across major Australia cities and states (Melbourne, Sydney, Brisbane, Tasmania and Western Australia)

## Overview
This project aims to use exploratory data analysis (EDA),  data visualisations and predictive modeling to uncover what makes an Airbnb listing succesful in the Australian market. It attempts to answer several questions such as: What is the optimal property size for a return on investment? What is the sweet spot for an Airbnb listing - how many bathrooms or bedrooms? What are the key differences between Airbnb listings across different states in Australia?

## Key Findings
- Review Scores are the strongest predictor and driver of revenue. Listings rated between 4.5 to 5.0 capture the majority of high-earning listings, while lower ratings hover around the zero mark. A high review score is necessary but not sufficient condition for maximising revenue
- Factors such as price, room type, reviews and availability are all important drivers of estimated revenue
- Using an XGBoost regression model, these listing characteristics were able to explain 66.1% of the variance in estimated revenue across the listings

## Limitations
- Other important factors such as listing photos, host responsiveness and listing description were missing from the dataset
- Seasonality is not accounted for

Data: Inside Airbnb (June, 2025) - https://insideairbnb.com/get-the-data/
