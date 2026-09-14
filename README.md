# Data Vortex: Social Engine — Data Cleaning & EDA

## Overview

This project focuses on cleaning and analyzing corrupted social media datasets as part of the **Data Vortex: Social Engine — Recovery Terminal** challenge.

The project uses Python to improve data quality, identify inconsistencies, and generate meaningful insights through Exploratory Data Analysis (EDA).

## Objectives

* Inspect the Users and Posts datasets
* Handle missing values
* Remove duplicate records
* Detect and correct invalid engagement values
* Standardize inconsistent timestamps
* Analyze user activity and platform engagement
* Generate visualizations and insights
* Export cleaned datasets

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Notebook Structure

### Data Inspection and Cleaning

**Cells 1–18**

This section includes:

* Dataset loading
* Shape and column inspection
* Missing-value analysis
* Duplicate detection
* Missing-value treatment
* Text cleaning
* Negative likes correction
* Timestamp standardization
* Data validation

### Exploratory Data Analysis

**Cells 19–30**

This section includes:

* Statistical summaries
* Platform-wise post counts
* Average likes, shares, and comments
* Most active users
* Follower-count distribution
* Language and location analysis
* Correlation heatmap
* Engagement-score calculation
* Users and Posts dataset merging
* Follower count vs engagement analysis

### Export

**Cells 31–32**

The cleaned datasets and merged analysis file are exported as CSV files.

## Dataset Files

* `Social_Engine_Users(1).csv`
* `Social_Engine_Posts_Corrupted(1).csv`

## Output Files

* `Social_Engine_Users_Cleaned.csv`
* `Social_Engine_Posts_Cleaned.csv`
* `Social_Engine_Merged_Analysis.csv`

## How to Run

1. Open the notebook in Google Colab.
2. Upload both original CSV files.
3. Run the cells in order.
4. Review the cleaning results and visualizations.
5. Download the cleaned datasets from the final cells.

## Key Cleaning Operations

* Missing platforms are labelled as `Unknown Platform`.
* Missing text content is labelled as `No text content available`.
* Missing likes are replaced with `0`.
* Duplicate records are removed.
* Negative likes are treated as invalid and replaced with `0`.
* Mixed timestamp formats are converted into a consistent datetime format.

## Conclusion

This project demonstrates how data cleaning and exploratory analysis can transform inconsistent social media data into a structured dataset suitable for further analysis and insight generation.
