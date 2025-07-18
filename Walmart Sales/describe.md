🏪 Retail Sales Performance & Economic Impact Analysis
📌 Project Overview

This project analyzes sales data from a global retail giant to identify key factors influencing revenue, including economic indicators (CPI, unemployment), environmental variables (temperature), and operational costs (fuel prices). We leverage machine learning to:

    Quantify how external factors impact weekly sales.

    Optimize pricing/discount strategies to minimize costs and maximize revenue.

🔗 Dataset Source: https://www.kaggle.com/datasets/mikhail1681/walmart-sales

📂 Dataset Description

Key Features:
Column Name	Description	Data Type	Business Relevance
Store	Unique store identifier	Integer	Location-based analysis
Date	Start date of sales week	DateTime	Trend analysis by time
Weekly_Sales	Target: Total sales (in USD)	Float	Revenue performance metric
Holiday_Flag	Holiday week (1=Yes, 0=No)	Binary	Seasonal impact assessment
Temperature	Average air temperature (°F)	Float	Weather-driven demand
Fuel_Price	Fuel cost per gallon (USD)	Float	Logistics cost driver
CPI	Consumer Price Index	Float	Purchasing power indicator
Unemployment	Regional unemployment rate (%)	Float	Economic health metric

🎯 Key Questions

    Economic Factors:

        How do CPI and unemployment correlate with sales?

        Do fuel prices disproportionately affect high-traffic stores?

    Environmental Influence:

        Does temperature drive sales for seasonal products?

    Temporal Trends:

        How much do holidays boost revenue compared to regular weeks?

    ML Optimization:

        Can we predict low-revenue weeks to trigger targeted discounts?

🛠️ Methodology

1. Exploratory Data Analysis (EDA)

    Time-series decomposition of sales trends.

    Correlation heatmaps (e.g., Features vs Weekly_Sales(Target)).

    Holiday vs. non-holiday sales comparisons.


2. Predictive Modeling

    Algorithms:

        Regression: XGBoost, LightGBM (for sales prediction).
   
📊 Expected Insights

✔ Revenue Drivers: Rank features by impact (e.g., Holiday_Flag > CPI).
✔ Risk Mitigation: Identify stores prone to revenue dips during high unemployment.
✔ Actionable Strategies: Recommend dynamic pricing adjustments for weather-sensitive.

💻 Technical Stack

    Data Processing: pandas, numpy

    Visualization: seaborn,matplotlib

    Machine Learning: scikit-learn, XGBoost, LightGBM

    Workflow: Jupyter Notebooks

    
