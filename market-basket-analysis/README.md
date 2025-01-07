# Telecommunication Product Association Analysis

## Overview
This project involves conducting a market basket analysis for a telecommunications company to uncover meaningful product associations among customer transactions. The goal is to use the Apriori algorithm to identify frequent itemsets and generate association rules based on transactional data. By analyzing metrics such as support, confidence, and lift, the project provides actionable insights that can be used to enhance marketing strategies, improve product placement, and increase cross-selling opportunities.

## Project Structure
- **Data Preprocessing**: Transformation of raw data into transactional data suitable for market basket analysis.
- **Association Rule Mining**: Implementation of the Apriori algorithm to extract frequent itemsets and generate association rules.
- **Metrics Analysis**: Evaluation of rules based on support, confidence, and lift to determine their significance and strength.
- **Insights & Recommendations**: Extraction of valuable business insights for cross-selling and upselling strategies.

## Files
- `teleco_market_basket.csv`: Raw transactional data.
- `cleaned_market_basket_data.csv`: Processed data used for analysis.
- `market_basket_analysis.py`: Python script for data preprocessing, association rule mining, and generating metrics.
- `output_screenshots/`: Folder containing screenshots of the top association rules.

## Requirements
- Python 3.x
- Pandas
- mlxtend

To install the necessary dependencies, run:

