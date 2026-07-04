# Correlation-Analysis
#  Movies Correlation Analysis

## Overview

This project performs **Exploratory Data Analysis (EDA)** and **Correlation Analysis** on a movies dataset to identify the factors that influence a movie's gross earnings. Using Python and popular data analysis libraries, the project examines relationships between numerical and categorical features through statistical methods and visualizations.

The analysis includes data cleaning, missing value inspection, correlation matrices, heatmaps, scatter plots, box plots, and company-wise revenue analysis.

---

## Objectives

- Explore the movies dataset.
- Identify missing values and data types.
- Detect potential outliers.
- Analyze relationships between movie features.
- Compute Pearson, Spearman, and Kendall correlation coefficients.
- Visualize correlations using heatmaps.
- Identify highly correlated feature pairs.
- Analyze company-wise gross revenue.

---

## Dataset
Dataset: Movies Dataset
Source: Kaggle (public dataset)
movies.csv


## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```

## Project Workflow

### 1. Data Loading

- Load the dataset using Pandas.
- Inspect data types.
- Check for missing values.

### 2. Data Cleaning

- Identify missing values.
- Remove duplicate records.
- Convert categorical variables into numerical codes for correlation analysis.

### 3. Exploratory Data Analysis

- Box plot for detecting outliers.
- Scatter plots:
  - Budget vs Gross Earnings
  - Score vs Gross Earnings
- Box plots and strip plots for Rating vs Gross.

### 4. Correlation Analysis

The project computes three correlation methods:

- Pearson Correlation
- Spearman Correlation
- Kendall Correlation

Heatmaps are generated to visualize relationships between variables.

### 5. Company Analysis

The project calculates:

- Total gross revenue by company.
- Top 15 highest-grossing production companies.
- Company revenue grouped by release year.

---

## Visualizations

The project includes several visualizations, such as:

- Correlation Heatmaps
- Budget vs Gross Scatter Plot
- Score vs Gross Scatter Plot
- Rating vs Gross Box Plot
- Rating vs Gross Strip Plot

---

## Key Insights

The analysis helps answer questions such as:

- Does a higher budget lead to higher gross revenue?
- How strongly are movie scores related to gross earnings?
- Which production companies generate the highest revenue?
- Which movie features are most strongly correlated?

---

## Results

Some key observations include:

- Budget shows a strong positive correlation with gross revenue.
- Gross revenue is influenced by multiple numerical features.
- Pearson, Spearman, and Kendall correlations provide different perspectives on feature relationships.
- Production companies vary significantly in total gross earnings.

