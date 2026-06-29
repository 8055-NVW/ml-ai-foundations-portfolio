# UK House Price Index: Machine Learning Data Preparation Project

## Project Overview

This project prepares the UK House Price Index dataset for future machine learning modeling.

The aim is to load, inspect, clean, and transform official UK housing data using Python and pandas. The prepared dataset could later be used to train a supervised machine learning model to predict average house prices based on location, time, and other housing market features.

## Project Goals

The main goals of this project are to:

* Load and inspect a real-world CSV dataset
* Clean and prepare the data for machine learning
* Identify useful feature columns and a target variable
* Handle missing values and inconsistent data
* Transform date and categorical columns into model-ready formats
* Prepare training and testing datasets
* Document the full data preparation workflow in a Jupyter Notebook

## Dataset

The dataset used in this project is the UK House Price Index full CSV file, downloaded from GOV.UK.

The raw dataset is stored locally as:

`data/uk_hpi_full.csv`

The dataset contains historical UK house price data across different areas and time periods. It includes information such as average prices, house price indices, sales volumes, property types, and regional identifiers.

Because the raw CSV file is large, it is not committed directly to this repository. The dataset can be downloaded from the GOV.UK UK House Price Index data downloads page.

## Machine Learning Task

The intended machine learning task is a supervised regression problem.

The target variable is:

`AveragePrice`

This represents the average house price for a given area and time period.

Possible feature variables may include:

* Date-based features, such as year and month
* Region or area information
* Sales volume
* Property-type information
* Buyer-type information

The final feature set will be selected after inspecting and cleaning the dataset.

## Project Workflow

The project follows these main steps:

1. Import Python libraries
2. Load the CSV dataset into pandas
3. Inspect the dataset structure
4. Check for missing values and duplicate rows
5. Clean and standardize columns
6. Convert date columns into datetime format
7. Select the target variable
8. Select useful feature variables
9. Remove columns that may cause data leakage
10. Encode categorical variables
11. Prepare training and testing datasets
12. Summarize the final machine-learning-ready dataset

## Tools Used

* Python
* pandas
* Jupyter Notebook
* Git
* GitHub

## Repository Structure

```text
ml-ai-foundations-portfolio/
│
├── data/
│   └── uk_hpi_full.csv
│
├── ml_ai_foundations_project.ipynb
├── README.md
└── .gitignore
```

## Current Status

Project setup and scoping are complete. The next stage is loading and inspecting the dataset in the Jupyter Notebook.
