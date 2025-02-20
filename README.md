# Household Energy Data Analysis

## Overview
This repository contains an Excel dataset (`household_energy.xlsx`) that provides insights into household energy consumption, costs, and reliability. The dataset includes information on household size, income levels, energy sources, and regional energy consumption trends.

## Dataset Contents
The Excel file consists of multiple sheets with detailed information:

### 1. Data
This sheet contains raw data with the following columns:
- **Household_ID**: Unique identifier for each household.
- **Household_Size**: Number of people in the household.
- **Income_Level**: Categorized as Low, Medium, or High.
- **Location_Type**: Urban or Rural.
- **Total_Energy_Consumption**: Total energy consumed by the household (in kWh).
- **Electricity_Consumption**: Energy consumption from electricity sources.
- **Alternative_Energy_Consumption**: Consumption from alternative energy sources (e.g., solar, biomass).
- **Renewable_Energy_Consumption**: Specific consumption of renewable energy.
- **Energy_Cost**: Total cost of energy consumption (in local currency).
- **Reliability_Index**: Score indicating the reliability of energy supply.
- **Energy_Source_Type**: Primary energy source (e.g., Biomass, Solar, Grid).
- **Date_Recorded**: Date when the data was recorded.

### 2. Cleaned Data
This sheet contains preprocessed data with additional computed values:
- **Energy_Efficiency (%)**: A measure of how efficiently energy is used.
- **Cost_per_Unit**: Cost of energy per unit consumption.

### 3. Energy_Consumption_HHSize
Summarized statistics on energy consumption based on household size:
- Average Total Energy Consumption per household.
- Average Electricity Consumption.
- Sum of Energy Cost.

### 4. Renewable_Energy_Income
Analyzes the relationship between income levels and renewable energy consumption:
- Average Renewable Energy Consumption for High, Medium, and Low-income groups.

### 5. Energy_Cost_Location
Breakdown of energy cost by location type (Urban/Rural):
- Count of energy source types.
- Alternative energy and electricity consumption.
- Total energy cost and cost per unit.

### 6. Energy_Reliability
Reliability index for different energy sources, split by location.

### 7. Energy_Cost_Analysis
Comparison of energy cost and cost per unit across various energy sources.

### 8. DashBoard
This sheet appears to be empty, possibly reserved for visualizations.

## Use Cases
This dataset can be useful for:
- **Energy Consumption Analysis**: Understanding household energy usage patterns.
- **Cost Analysis**: Investigating energy costs by location, income level, and energy type.
- **Renewable Energy Adoption**: Examining the impact of renewable energy sources on households.
- **Energy Reliability Study**: Assessing energy reliability across different sources.

## How to Use
1. Load the dataset into a Python environment using `pandas`:
   ```python
   import pandas as pd
   df = pd.read_excel("household_energy.xlsx", sheet_name="Data")
   ```
2. Perform exploratory data analysis (EDA) and visualization using `matplotlib` or `seaborn`.
3. Develop predictive models for energy consumption trends using `scikit-learn`.

## Future Work
- Add data visualizations to the `DashBoard` sheet.
- Implement machine learning models to predict energy consumption and costs.
- Enhance data cleaning and outlier detection.

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request.

## License
This project is open-source and available for educational and research purposes.

![Dashboard Image](path/to/dashboard_image.png)

[Download Research PDF](path/to/research.pdf)
