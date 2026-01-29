✈️ Understanding Flight Delays in Houston Airports (IAH & HOU)
A Data Science Project Analyzing Weather, Airport Conditions, and Flight Delay Patterns (2020–2024)
This project investigates the key factors influencing flight delays at Houston's two major airports:

George Bush Intercontinental Airport (IAH) and William P. Hobby Airport (HOU).

Using real-world datasets from 2020–2024, we analyze how weather, airport characteristics, and operational factors contribute to delay patterns.

Our workflow includes data integration, cleaning, EDA, statistical analysis, and predictive modeling.

🧠 Project Motivation
Anyone who has flown out of Houston knows one thing:

“Houston flights don’t delay—they just take emotional time to prepare.”

This project aims to scientifically understand why delays happen, identify key contributing variables, and create a clean unified dataset for accurate analysis and modeling.

📂 Datasets Used
1. Flight Delay Data (IAH & HOU)
Monthly arrival delay statistics:

Carrier delay

Weather delay

NAS delay

Security delay

Late aircraft delay

Cancelled & diverted flights

Total arrival flights

2. Weather Data (IAH & HOU, hourly/daily)
Variables include:

Temperature

Dew point

Humidity

Precipitation

Snow

Wind speed / gust

Pressure

Weather condition code

3. Airport Metadata
Airport code & name

City, state, country

Latitude, longitude

Elevation

Climate zone

📊 Key Features & Outcomes
✔ Clean, unified dataset (1107 rows × 44 columns)
✔ 0 missing values
✔ Converted hourly weather → monthly means
✔ Accurate 1-to-1 merge of all data sources
✔ Seasonal, carrier-wise, and airport-wise delay analysis
✔ Statistical insights on weather impact
✔ Predictive models to estimate delay likelihood
🧼 Data Cleaning Highlights
Standardized inconsistent column names

Removed duplicates across all datasets

Fixed missing values (tsun dropped due to 100% NaN)

Imputed minor missing values (e.g., arr_del15)

Created unified Date, Year, Month, Season fields

Performed safe merging to avoid duplication

Final validation of complete dataset

📈 Exploratory Data Analysis
Includes:

Delay distribution histograms

Top carriers with maximum delays

Seasonal variation plots

Airport-level delay patterns

Weather vs delay correlation heatmaps

Monthly delay trend lines

📐 Statistical Analysis
Performed:

Correlation analysis

Hypothesis testing

Delay factor ranking

Weather impact quantification

Key variable identification

🤖 Predictive Modeling
Models implemented:

Linear Regression

Random Forest

Gradient Boosting

Feature importance analysis

Cross-validation

Performance comparison
