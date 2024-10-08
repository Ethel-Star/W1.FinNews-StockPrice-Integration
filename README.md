# A Data-Driven Exploration of Financial News and Stock Market Dynamics
# Project Overview
This repository contains Jupyter notebooks designed to enhance financial forecasting at Nova Financial Solutions through comprehensive data analysis. The project focuses on three key areas:

# Sentiment Analysis:

Objective: Quantify the sentiment expressed in financial news headlines to understand the tone and emotional context.
Approach: Use Natural Language Processing (NLP) techniques to compute sentiment scores for each headline. These scores are then associated with their respective stock symbols.

# Correlation Analysis:

Objective: Establish statistical correlations between sentiment scores and stock price movements.
Approach: Merge sentiment scores with stock price data and analyze how sentiment impacts stock performance. Track price changes around the publication dates of news articles and evaluate correlations to derive actionable insights.
Stock Performance Analysis with TA-Lib:

Objective: Assess stock performance using technical indicators from TA-Lib.
Approach: Apply technical indicators such as moving averages, Relative Strength Index (RSI), and Bollinger Bands to historical stock price data. Analyze these indicators to evaluate stock performance and identify trends.
Notebooks
1. EDA_Financial_Headlines.ipynb
Purpose: Perform sentiment analysis on financial news headlines.
Key Steps:
Load and preprocess the financial news dataset.
Extract sentiment scores using NLP techniques.
Visualize sentiment distribution and trends.

3. TALib_Quant_Analysis.ipynb
Purpose: Assess stock performance using technical indicators from TA-Lib.
Key Steps:
Load historical stock price data.
Apply TA-Lib technical indicators (e.g., moving averages, RSI, Bollinger Bands).
Analyze and visualize stock performance and trends based on these indicators.
2. Correlation_Analysis.ipynb
Purpose: Analyze the correlation between sentiment scores and stock price changes.
Key Steps:
Merge sentiment data with stock price data.
Track stock price changes around publication dates of news articles.
Compute and visualize correlations between sentiment and stock performance.