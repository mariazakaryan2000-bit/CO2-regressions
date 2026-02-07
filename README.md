# CO₂ Emissions Analysis

## Project Description
This project analyzes how various factors influence CO₂ emissions across countries using World Bank data. The dataset includes 217 countries and 8 explanatory variables, with natural logarithmic transformations applied to three variables.

## Data
Data were collected from the World Bank database for the period 2018–2024. Missing values were imputed using the median, and country-level averages were computed to ensure one observation per country.

## Methods
- Data cleaning and preprocessing  
- Aggregation of yearly data to country-level averages  
- Logarithmic transformation for selected variables
- Linear regression was performed to analyze the impact of various factors (GDP per capita, renewable energy consumption, energy intensity, urban population, and trade) on CO₂ emissions. Logarithmic transformations were applied to selected variables to improve model interpretability and fit.

## Results
GDP per capita is a strong driver of CO₂ emissions: a 1% increase in GDP per capita leads to ~0.6% higher CO₂ emissions per capita.  
- Renewable energy consumption reduces CO₂ emissions։ a 1% increase in renewable share decreases emissions by ~0.57%.
- Logarithmic transformations improved model fit (R² increased from 0.44 to 0.70) and interpretability.

## How to Run
1. Install required packages: `pip install -r requirements.txt`  
2. Open notebooks in Jupyter Lab/Notebook
