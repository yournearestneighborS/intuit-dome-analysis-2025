# Los Angeles Clippers Arena Store Analysis

## Overview
This project analyzes fan purchasing behavior and store performance at the Los Angeles Clippers’ Intuit Dome using transaction-level sales and foot traffic data from three NBA playoff games.

The goal was to identify key revenue drivers, understand time-based demand patterns, and provide actionable business recommendations to improve in-arena sales and operations.

---

## Objectives
- Analyze customer purchasing behavior across game days
- Identify peak sales periods and underperforming time windows
- Compare performance across store types (Concessions vs. Retail)
- Determine key revenue drivers by business vertical
- Provide data-driven recommendations to optimize revenue

---

## Dataset
The analysis uses a dataset with purchase and foot trafic data over the course of three NBA Playoff games between the Los Angeles Clippers and the Denver Nuggets. This is from the 2025 Clippers Business Insights Data Challenge

---

## Methodology

### 1. Data Cleaning & Preparation
- Standardized column names and formats
- Converted timestamps to datetime objects
- Cleaned and aligned key identifiers across datasets

### 2. Data Integration
- Merged datasets using store identifiers and checkpoint mappings
- Linked transaction data with foot traffic data to analyze conversion patterns

### 3. Feature Engineering
- Extracted hourly time features from transaction timestamps
- Created aggregated views of transactions by store and time

### 4. Exploratory Data Analysis (EDA)
- Analyzed transaction volume by hour and location
- Identified peak and low-performing periods
- Compared revenue across store types and business verticals

### 5. Visualization
- Built charts to highlight peak vs. low demand periods
- Visualized revenue distribution across store categories

---

## Key Findings

- **Peak sales occur between 6–8 PM**, primarily pre-game and around halftime  
- **Significant drop in activity after 9 PM**, indicating low post-game engagement  
- **Food & Beverage dominates revenue**, contributing ~99% of sales in mixed-format stores  
- Retail stores generate substantial revenue independently but are secondary overall  

---

## Business Recommendations

- Optimize staffing and inventory during peak hours  
- Implement **mobile ordering** to reduce congestion and improve conversion  
- Introduce **bundle and loyalty deals** (food + merchandise)  
- Launch **post-game promotions** to increase late-hour sales  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Skills

Data Cleaning, Data Wrangling, Data Integration, Exploratory Data Analysis (EDA), Data Visualization, Feature Engineering, Time Series Analysis, Business Analytics, Data-Driven Decision Making

---

## Project Structure
```
├── data/
├── notebook/
├── report/
├── README.md
```
---

## Author
Oluwaseyi Caleb Folorunso
