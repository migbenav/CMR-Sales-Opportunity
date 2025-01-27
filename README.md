# CMR-Sales-Opportunity
B2B sales pipeline data from a fictitious company that sells computer hardware, including information on accounts, products, sales teams, and sales opportunities.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Objectives](#key-objectives)
- [Folder Structure](#folder-structure)
- [Requirements](#requirements)
- [Data Sources](#data-sources)


## Project Overview
This project focuses on analyzing and visualizing sales opportunities from a CMR (Customer Management Relationship) system. The goal is to provide an in-depth look into the sales pipeline, identify potential bottlenecks, and explore factors contributing to successful opportunities.
The repository includes Python code for data processing, analysis, and visualization. 

## Key Objectives:
- Evaluate sales team performance relative to each other.
- Identify sales agents who may be underperforming.
- Detect quarter-over-quarter trends.
- Determine which products have better win rates.
- Analyze Win/Lost opportunities in the prospecting and engaging stages.
- Predict outcomes for opportunities using closed opportunities flagged as win/lost.

## Folder Structure
The project files are organized as follows:

- **data/**: Contains the raw data files, such as `sales_pipeline.csv`, `products.csv`, `sales_teams.csv`, `accounts.csv`, and the data dictionary.
- **`notebooks/`**  
  Contains Jupyter notebooks for different stages of the analysis:
  - `CRM Sales - Data Loading and Cleaning.ipynb`: Initial data cleaning and preprocessing.
  - `CRM Sales Analysis 01.ipynb`: Features a Sankey diagram illustrating stages and opportunities in each stage. [Ploty Chart](https://nbviewer.org/github/migbenav/CMR-Sales-Opportunity/blob/main/notebooks/CMR%20Sales%20Analysis%2001.ipynb)
  - `CRM Sales Analysis 02.ipynb`: In-depth analysis of sales team performance.
  - `CRM Sales Analysis 03.ipynb`: Identification of underperforming sales agents.
  - `CRM Sales Analysis 04.ipynb`: Quarter-over-quarter trend analysis.
  - `CRM Sales Analysis 05.ipynb`: Product win rate analysis.
  - `CRM Sales Analysis 06.ipynb`: Predictions for Win/Lost opportunities in the prospecting and engaging stages using XGBoost.
- **visuals/**: Contain Link to tableau Public Dashboard
- **README.md**: This file, providing an overview and instructions.

## Requirements

The project uses Python and the following key libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost

## Data Sources
The analysis uses CMR Sales Opportunity data from [MAVEN](https://mavenanalytics.io/data-playground?accessType=open&dataStructure=Multiple%20tables&order=date_added%2Cdesc&tags=Business)
