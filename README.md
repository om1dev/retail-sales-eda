# Retail Sales EDA

## Project Overview
This repository contains an Exploratory Data Analysis (EDA) project for a retail sales business scenario using the Superstore dataset.

The goal is to understand:
- Sales performance across products, categories, and regions
- Customer purchasing patterns
- Profitability behavior (including the impact of discounting)

The analysis is designed to generate actionable business insights for decision-making.

## What Is EDA?
Exploratory Data Analysis (EDA) is the process of inspecting, summarizing, and visualizing data before advanced modeling.

In this project, EDA is used to:
- Check data structure and quality
- Detect potential issues (missing values, outliers, data type problems)
- Build an initial understanding of business trends in sales and profit
- Prepare clean, reliable data for deeper analysis

## Repository Structure
```
retail-sales-eda/
|-- data/
|   `-- Sample.csv
|-- notebooks/
|   |-- notebbok1.ipynb
|   `-- notebook2.ipynb
|-- images/
|-- src/
`-- README.md
```

## Dataset
- Source: Superstore Sales Dataset (Kaggle)
- File used: `data/Sample.csv`
- Encoding used while loading: `latin1`

### Data Snapshot From Current EDA
- Shape: `9994 rows x 21 columns`
- Key numeric fields: `Sales`, `Quantity`, `Discount`, `Profit`
- Current missing value check: `No missing values detected in any column`

## EDA Work Completed
Primary work is in `notebooks/notebbok1.ipynb`.

Completed stages:
1. Project setup and business context notes
2. Data loading with pandas
3. Initial inspection using:
	- `df.head()`
	- `df.head(10)`
	- `df.shape`
	- `df.dtypes`
	- `df.isnull().sum()`

Current result:
- Dataset is loaded successfully
- Data types are identified
- Baseline data quality check confirms no null values

## Work In Progress
`notebooks/notebook2.ipynb` starts the outlier analysis task.

Planned/ongoing next steps:
- Detect outliers in relevant numeric columns using boxplots
- Create labeled visualizations for outlier interpretation
- Summarize business impact and recommended handling strategy

## How To Run
1. Create and activate a Python environment.
2. Install required libraries:
	- `pandas`
	- `matplotlib`
	- `seaborn`
	- (optional) `plotly`
3. Open the notebooks in Jupyter/VS Code and run cells in order.

## Business-Focused EDA Questions For This Project
- Which categories and sub-categories drive the highest sales and profit?
- Which segments and regions are most valuable?
- Where does discounting hurt profitability?
- Which products or locations need attention due to consistent losses?

## Project Status
This project currently covers setup, loading, and foundational inspection. It is ready for deeper visual EDA and insight reporting in the next iteration.