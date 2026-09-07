# Seasonal Agriculture Performance Analysis

This project performs an exploratory data analysis (EDA) on a synthetic dataset related to agricultural performance across various farms, crops, and seasons. The goal is to uncover insights into factors influencing crop yield, production, and profitability, and to understand seasonal trends and regional variations in agricultural practices.

## Dataset

**File Name**: `seasonal_agriculture_performance_dataset.csv`

This dataset contains detailed information about agricultural performance, including:

*   **Farm Identifiers**: `Farm_ID`, `State`, `District`, `Crop`, `Season`
*   **Farm Characteristics**: `Farm_Area_Hectares`
*   **Environmental Factors**: `Rainfall_mm`, `Avg_Temperature_C`, `Humidity_pct`, `Sunlight_Hours_Day`, `Soil_pH`, `Soil_Moisture_pct`
*   **Inputs & Practices**: `Nitrogen_kg_ha`, `Phosphorus_kg_ha`, `Potassium_kg_ha`, `Irrigation_Method`, `Fertilizer_kg_ha`, `Pesticide_Litre_ha`, `Seed_Quality_Score`, `Water_Used_m3`
*   **Performance & Output**: `Yield_Tonnes_Ha`, `Production_Tonnes`, `Water_Efficiency_t_per_1000m3`, `Disease_Pest_Risk_pct`
*   **Financial Metrics**: `Market_Price_INR_Tonne`, `Total_Cost_INR`, `Revenue_INR`, `Profit_INR`

## Data Preprocessing

*   Missing values in `Rainfall_mm`, `Soil_Moisture_pct`, and `Yield_Tonnes_Ha` were imputed using the mean for each respective `Season`.
*   No duplicate rows were found.

## Key Findings from Exploratory Data Analysis

The analysis revealed several important insights:

*   **Kharif Season** generally exhibits the highest average crop yield and profitability, despite experiencing higher rainfall and moderate temperatures.
*   **Zaid Season** was found to be the least profitable, with a significant percentage of farms incurring losses. This season is characterized by higher temperatures and moderate water usage.
*   **Chilli and Sugarcane** crops showed high profitability, especially during the Kharif season.
*   **Rainfed and Drip irrigation methods** demonstrated superior water use efficiency compared to Sprinkler and Flood methods.
*   A notable **positive correlation exists between Rainfall, Yield, and Profit**, as well as with Disease/Pest Risk. This suggests that while rainfall is crucial for agricultural success, it also introduces increased challenges related to disease and pest management.
