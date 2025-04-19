# used_cars

🚗 Used Car Price Analysis

📘 Project Title

Uncovering Value: Analyzing Used Vehicle Prices by Condition, Mileage, Type, and Brand

🧭 Executive Summary

I analyzed over 150,000 used car listings across the U.S. to understand what drives price variation. Using Python, I explored how price is impacted by vehicle condition, mileage, manufacturer, and type. This analysis identifies high-value brands, price drop thresholds, and resale insights that could be used in consumer platforms or dealer pricing tools.

🧱 Project Structure

🧹 1. Data Cleaning & Preparation

Removed outliers (e.g., prices below $1,000 or above $100,000)

Filtered mileage to <150,000 for realistic resale comparisons

Filled or dropped missing values in condition, manufacturer, type

🔍 2. Exploratory Data Analysis (EDA)

✅ Part A: General Market Overview

Average price and mileage of all listings

Distribution of vehicle conditions and types

✅ Part B: Price Influencers

Condition: Boxplot — price rises sharply from “fair” to “like new”

Vehicle Type: SUVs & trucks have highest medians

Mileage: Scatterplot — price declines noticeably after 100k miles

✅ Part C: Brand Value Comparison

Top manufacturers by average price (under 150k miles)

Price vs. mileage curve for selected brands (e.g., Toyota vs. BMW)

✅ Part D: Insightful Combinations

Best value by type + condition (e.g., trucks in good condition)

Heatmap or grouped bar chart

📈 3. Dashboard or Visual Report (Optional)

Interactive filters: brand, type, year, mileage

Insights panels: average price, odometer bands, value outliers

🧠 4. Key Insights

Vehicle condition is one of the strongest price indicators

SUVs and trucks maintain value longer than sedans or hatchbacks

Some manufacturers (Toyota, Ford) balance price and reliability well

Listings with “unknown” condition or missing info show major price drops — could be flagged in product UI

🛠️ 5. Tools Used

Python (Pandas, Matplotlib, Seaborn)

Jupyter Notebook
