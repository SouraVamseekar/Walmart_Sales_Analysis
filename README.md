# Walmart Sales Analysis
This project analyzes Walmart Store Sales data to uncover insights and build predictive models for sales forecasting. The analysis and modeling are performed using Python in a Jupyter Notebook.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Features](#key-features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Project Overview
The goal of this project is to analyze Walmart sales data, identify patterns, and build a predictive model to forecast sales for Store 1. Key tasks include:
- Basic exploratory data analysis (EDA).
- Holiday sales impact analysis.
- Monthly and semester-wise sales trends.
- Building predictive models (Linear Regression, Random Forest).

## Dataset
- The dataset includes weekly sales data for Walmart stores along with associated economic indicators such as CPI, unemployment rate, and fuel prices.
- **Columns**:
  - `Store`: Store ID.
  - `Weekly_Sales`: Weekly sales for the store.
  - `Holiday_Flag`: Whether the week is a holiday (1) or not (0).
  - `Temperature`: Average temperature in the region.
  - `Fuel_Price`: Cost of fuel in the region.
  - `CPI`: Consumer Price Index.
  - `Unemployment`: Unemployment rate in the region.

## Key Features
- Exploratory data analysis to identify trends and patterns.
- Time-based sales analysis (monthly, semester, and quarterly).
- Modeling and prediction using:
  - **Linear Regression**
  - **Random Forest Regressor**
- Comparison of model performance (MSE and \(R^2\)).

## Requirements
See the [Requirements](#requirements) section for dependencies.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/walmart-sales-analysis.git
   cd walmart-sales-analysis
