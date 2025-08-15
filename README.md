# Real Estate Data Science Project, Gurgaon, India

## Overview
This project is a real estate analytics and prediction system focused on the Gurgaon property market. It includes:
1. **Price Prediction Module**: Machine learning models for accurate property price estimation.
2. **Analytical Module**: Generates insights from the market data.
3. **Recommendation System**: Personalized property suggestions based on user preferences.

The goal is to help buyers, sellers, and investors make informed decisions by combining scraped real estate data with data science techniques.

---

## Problem Statement
In Gurgaon’s rapidly growing real estate market, increasing urbanization and limited land availability create a demand for:
- Accurate price prediction
- Market insights
- Personalized property recommendations

---

## Datasets
- **Source**: Scraped from 99acres and other property listing websites.
- **Raw Data**:  
  - Flats dataset: 3018 rows × 17 columns  
  - Houses dataset: 1045 rows × 18 columns  
- **Cleaned & Merged Dataset**: 3555 rows × 13 selected features after:
  - Data cleaning, including handling missing values and removing outliers
  - Feature engineering, such as luxury score, furnishing details, and age of possession
  - Feature selection using correlation, Random Forest, and RFE

---

## Methodology
1. **Data Collection**: Web scraping from multiple property listing sources.
2. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Removing outliers
   - Encoding categorical variables
3. **Exploratory Data Analysis**
   - Univariate and multivariate analysis
   - Pandas Profiling for distribution patterns
4. **Feature Engineering**
   - Additional room indicators
   - Area with type specification
   - Age of possession
   - Furnish details and luxury score
5. **Model Selection & Training**
   - Compared several ML models for price prediction
   - Evaluated performance using metrics like RMSE and R²
6. **Recommendation System**
   - Content-based filtering using property features
7. **Insights Generation**
   - Market trends
   - Pricing heatmaps
   - Supply-demand insights 
