# Real Estate Investment Prediction with Zillow Data
![Housing Image](/images/housing.png "Real Estate Investment")

## Overview
This repository contains the analysis of historical median house prices sourced from Zillow, covering the period from April 1996 to April 2018. The project's objective is to pinpoint the top locations within the US for real estate investment, utilizing time series forecasting methods.

## Goal
The goal of this project is to accurately predict the top 5 investment locations in the United States based on the Return on Investment (ROI) calculated from Zillow's historical median house prices data.

## Data
The primary dataset comprises Zillow's historical median house prices for a range of US locations. This dataset was cleaned and preprocessed to address inconsistencies and missing values before analysis.

## Analysis
The following steps were taken to analyze the data:
- Conducting time series analysis to uncover underlying trends and seasonal patterns in house prices.
- Developing and tuning a Seasonal Autoregressive Integrated Moving Average (SARIMA) model to forecast future median house prices.
- Comparing the SARIMA model's performance against the Facebook Prophet model.

## Key Findings
1. **Top Investment Locations (based on ROI):**
   - Upper East Side, New York
   - Sea Island, Georgia
   - Manhattan, New York
   - Brooklyn, New York
   - Hanalei, Hawaii

2. **Factors Influencing House Prices:**
   - Proximity to beaches and outdoor activities had a positive impact on house prices.
   - The level of urbanization showed no significant impact on pricing trends.

3. **Model Performance:**
   - The SARIMA model with dynamic forecasting demonstrated superior performance compared to the Facebook Prophet model.

## Recommendations
- **Target Areas:** Focus on locations with natural amenities like beaches, which show a positive correlation with house price appreciation, particularly in California, Florida, and Colorado.
- **High ROI Locations:** New York, Hawaii, and Georgia emerged as regions with promising ROI, although potential investors should be cautious of future price drops, especially in New York.
- **Risk Aversion:** Investors seeking stability should avoid areas with high price volatility, such as Boston, New Ulm, New Castle (Ohio), and Dublin.

## Usage
To replicate this analysis or to apply the methodology to other datasets:
1. Clone this repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter notebook `Time-Series-Modelling.ipynb` to view the analysis and results.

## Contributing
Interested in contributing? We welcome pull requests and new insights that could enhance the prediction model or extend the analysis.
