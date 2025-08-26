# EDA-NYC-taxi

This project presents an exploratory data analysis (EDA) of the NYC Taxi dataset (2023) to identify financial and temporal patterns.
1. Data Prep → Sampling, cleaning, and preprocessing of trip records
2. Analysis → Revenue trends, peak demand hours, seasonal patterns
3. Insights → Business strategies to optimize operations and boost profits

## Dataset

Source: NYC Taxi & Limousine Commission (TLC)
Year: 2023
Sample Size: ~6,00,000 entries
Features: Pickup/Dropoff time, trip distance, passenger count, fare, tips, total amount, etc. <br>
[Full dataset (Parquet format)](https://drive.google.com/drive/folders/1W9Uyo0Sy4Qdm-eBb5WQiedEonyIMmukm?usp=drive_link) – hosted externally due to size limits.

## Approach

### Data Cleaning & Preprocessing
Handling missing values, outliers, errenous data
Engineered features (e.g., trip duration, revenue per mile)

### Exploratory Data Analysis
Financial Analysis: Revenue distribution, average fare, tip trends
Temporal Analysis: Hourly, daily, monthly ride patterns
Geospatial analysis: Pickup & dropoff hotspots

### Visualization
Bar graphs, box plots, scatter plots, heat maps to reveal hidden trends

## Tech Stack

* Python (Pandas, NumPy)
* Matplotlib, Seaborn, Plotly for visualization
* Jupyter Notebook for analysis
