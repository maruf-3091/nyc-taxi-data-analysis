## NYC Taxi Data Analysis & Feature Engineering

## Project Overview
This project performs end-to-end Data Cleaning, Feature Engineering, and Exploratory Data Analysis (EDA) on the New York City (NYC) Taxi dataset using Python and Pandas. The primary objective is to uncover key business insights regarding trip metrics, fare distributions, and passenger tipping behavior.

##  Key Data Operations & Workflow
1. **Data Cleaning & Filtering:**
   * Handled missing values in pickup/dropoff locations and borough data.
   * Filtered out invalid records (e.g., zero or negative trip distances, zero fares).

2. **Feature Engineering:**
   * Calculated trip duration in minutes (`duration_minutes`).
   * Computed unit fare cost (`fare_per_mile`).
   * Extracted temporal attributes such as pickup hour (`pickup_hour`).

3. **Data Aggregations & Pivot Tables:**
   * Analyzed trip volume across routes (`pickup_borough` vs `dropoff_borough`).
   * Evaluated average fares across boroughs based on payment methods (`payment`).
   * Calculated passenger tipping habits across taxi colors (`yellow` vs `green`) and payment types.

## Key Business Insights
* **Payment Method & Tipping:** Credit card payments yield recorded tipping data, whereas cash payments show zero system-recorded tips.


## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib
* **Environment:** Google Colab / Jupyter Notebook
