# Hotels-Operations-Analysis-EDA

<div align="center">

<img src="hotel.webp" alt="drawing" width="500"/>

</div>

## Overview
Comprehensive analysis of 119K+ hotel bookings (2015-2017) uncovering cancellation patterns, revenue trends, and customer behavior insights. Built predictive models and actionable recommendations for hotel revenue optimization. (38 words)

## Dataset Overview
- **Size**: 119,390 bookings from City Hotel (79K) & Resort Hotel (40K)
- **Time Period**: 2015-2017 with arrival dates across all months
- **Key Metrics**: 37% cancellation rate, avg ADR $101.83, avg lead time 104 days
- **32 Features**: Demographics (adults/children), booking details (lead_time, market_segment), financials (ADR), reservation status
- **Data Quality**: Minimal missing values, agent/company fields have some NaNs
- **Market Segments**: Online TA (56K), Groups, Corporate, Direct bookings

## Analysis
- **EDA**: Cancellation rates by month/hotel type (City: 41.7% vs Resort: 27.8%), seasonal revenue peaks (Aug: $7.9M)
- **Visualizations**: Heatmaps, boxplots, correlation analysis, revenue by market segment
- **Feature Engineering**: Total nights, revenue calculation (ADR × nights), room type grouping
- **Insights**: Special requests correlate with higher ADR ($130+ for 4+ requests), new guests stay longer (3.5 vs 1.9 nights)
- **Predictions**: Built ML models for cancellation forecasting using key predictors like deposit_type, lead_time
- **Recommendations**: Dynamic pricing for high-cancellation periods, target repeat guests, optimize room upgrades

## How to Use
- Clone repo:
  ```git
  git clone https://github.com/PratyushPuri/Hotels-Operations-Analysis-EDA.git`
  ```
- Install dependencies:
  ```python
  pip install -r requirements.txt
  ```
  (pandas, seaborn, scikit-learn)
- Open `hotel-booking-demand-analysis.ipynb` in Jupyter/Colab
- Run cells sequentially - data loads automatically
- Original Kaggle: [hotel-booking-demand-analysis](https://www.kaggle.com/code/pratyushpuri/hotel-booking-demand-analysis)
- Customize: Modify hyperparameters in ML section or add new features
- Deploy: Save models with joblib for production use

## Author & Contact
- Name: `Pratyush Puri`
- Contact: `pratyushpuri17@gmail.com` / [LinkedIn](https://www.linkedin.com/in/pratyushpuri)
