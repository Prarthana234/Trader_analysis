# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) affects trader behavior and performance on Hyperliquid.

## Methodology
1. Data cleaning and preprocessing
2. Timestamp conversion
3. Merging trader data with market sentiment
4. Feature engineering (PnL, trade size, trade frequency)
5. Visualization and analysis

## Insights
- Average PnL tends to be higher during Greed sentiment periods.
- Trade activity increases during Fear periods.
- Large position traders experience higher PnL volatility.

## Strategy Recommendations
1. Reduce leverage during Fear periods to control risk.
2. Trend-following strategies perform better during Greed sentiment.

## Dataset
Datasets are large and not included in this repository.

Download them from:

Bitcoin Market Sentiment:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

Historical Trader Data:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

## Requirements

Install dependencies:

pip install pandas numpy matplotlib seaborn
