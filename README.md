# German Electricity Market Analysis

This repository contains a series of ipynb notebooks analyzing the German electricity market using fundamental supply and demand factors across European markets, with a focus on understanding price dynamics and forecasting German electricity prices (`Price_de`).

## Overview

1. **1_German_Power_Price_Analysis.ipynb**  
   Performs **Data Exploration and Understanding**:  
   - Examines dataset structure, time period, and observation frequency   
   - Performs an initial analysis of German electricity prices

2. **2_Covariate_Analysis.ipynb**  
   Explores the **relationship between fundamental variables and German prices**:  
   - Analyzes supply-demand balance and correlations with German demand (`Demand_de`)  
   - Studies the impact of renewable generation (`Solar_de`, `Wind_de`)  
  
3. **3_Peak_Hour_Analysis.ipynb**  
   Focuses on **morning and evening price spikes**:  
   - Quantifies the magnitude of peak hour price spikes  
   - Analyzes demand and renewable generation during peak and off-peak hours  
   - Performs a merit order analysis to identify the generation technologies contributing most to price formation  

4. **4_Model_Development.ipynb**  
   Develops a **predictive simple model for German electricity prices**:  
   - Performs feature engineering, including time-based features, lags, and net demand  
   - Builds a simple linear regression model using a subset of fundamental variables  
   - Evaluates model performance and examines how well it captures peak hour price spikes  

This workflow provides a comprehensive view of the drivers of German electricity prices and demonstrates a simple mean forecasting approach using fundamental market data.
