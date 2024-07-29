# Time-Series-Analysis-Zillow-Data

## Project Description
## Overview / Background 
In the competitive world of real estate investment, making informed decisions is crucial for maximizing returns and minimizing risks. The real estate market is influenced by numerous factors, including economic conditions, demographic trends, and local market dynamics. For a fictional real-estate investment firm looking to expand its portfolio, identifying the most promising zip codes for investment requires a data-driven approach. This project aims to analyze historical housing data to identify trends and patterns that can inform investment decisions. By developing a predictive model, we aim to forecast future returns on investment (ROI) for different zip codes, providing valuable insights for prospective investors.

# Problem Statement
The real estate market is experiencing unpredictable fluctuations in property prices. This uncertainty makes it difficult for prospective investors to make informed decisions about investing in property. The company needs to find an informed way to decide on which properties to invest in.

# Objectives

1. To analyze the zillow housing dataset, identify key patterns, trends and relatioships in the data and yeild visualizations that will aid in data-driven decisions.
2. To develop a predictive timeseries model that will forecast return on investment(ROI) of the various Zip codes.

## Data Sources
The data used in this project is sourced from Zillow Research, a leading real estate and rental marketplace. The dataset includes historical housing data for 147 zip codes in the United States, spanning the years 1996 to 2018. The dataset contains information on median home prices, rental prices, and housing sales volume for each zip code. The data is organized in a wide format, with each row representing a unique zip code and each column representing a specific year. The dataset also includes metadata on the location and population of each zip code, providing additional context for the analysis.

## Data Understanding
The dataset consists of various columns including region information and monthly real estate prices from April 1996 to April 2018. 
The columns are:
- RegionID: Identifier for the region
- RegionName: Zip code
- City: City name
- State: State abbreviation
- Metro: Metropolitan area
- CountyName: County name
- SizeRank: Rank based on size
- Date columns that run from  1996-04 to 2018-04: Real estate prices for each month


## Conclusion
* Market Dynamics: The real estate market exhibits significant geographic disparities in terms of property count, average median house prices, and ROI. California dominates the market, followed by New York and Texas.
* Price Trends: Historical data reveals a general upward trend in real estate prices with a notable peak around 2006, followed by a decline and subsequent recovery.
* ROI Variability: Return on Investment (ROI) varies significantly across cities and timeframes, emphasizing the complex nature of real estate investments. 
* Data Stationarity: The time series data is stationary, which is essential for accurate time series modeling.
* Seasonal Patterns: No significant seasonal patterns were observed in the data.
* Model Performance: The ARIMA(2,1,0) model demonstrated superior performance compared to the baseline ARIMA(1,0,0) model, effectively capturing the underlying patterns in the data.

## Recommendations
* Target High-Growth Regions: Given the substantial variations in ROI across cities, prioritize investment in regions with consistently high historical returns, such as Palo Alto and Water Mill.
* Diversify Investment Portfolio: To mitigate risks associated with real estate investments, consider diversifying across different geographic locations and property types.
* Long-Term Investment Horizon: The analysis suggests that longer investment horizons might yield higher returns, although this varies across cities.
* Continuous Monitoring: Regularly monitor market trends and adjust investment strategies accordingly.
* Risk Assessment: Conduct thorough risk assessments for each investment opportunity, considering factors such as economic indicators, demographic changes, and local market conditions

# Next steps
* Incorporate External Factors: Expand the analysis by incorporating macroeconomic indicators (e.g., interest rates, GDP) to improve forecast accuracy.
* Advanced Modeling Techniques: Explore advanced time series models (e.g., SARIMA, LSTM) to capture complex patterns in the data.
* Risk Modeling: Develop a comprehensive risk assessment framework to quantify investment risks.
* Portfolio Optimization: Utilize optimization techniques to construct optimal investment portfolios based on risk and return preferences.
* Real-Time Data Integration: Establish a system for real-time data ingestion to enable timely decision-making.

# Trello Link
https://trello.com/b/JTac8Mqq/phase-4-group-project
