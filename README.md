# Supplier-Invoice-EDA

### Overview
This repository contains an Exploratory Data Analysis (EDA) of supplier invoices, conducted in R and presented in an R Markdown file. The goal is to analyze supplier relationships, invoice volumes, and spending patterns in a supply chain context.

### Contents
* Supplier_Invoice_EDA.Rmd: R Markdown file with data cleaning, transformation, and analysis.
* Supplier_Invoice_EDA.html: HTML output for easy viewing of the EDA results.
* README.md: Project overview and usage instructions.
upplier_data.csv is loaded, which contains sample data on supplier invoices.
al invoice amounts per month, visualized with line plots.

### Analysis Structure
1. Preparing Environment: Installs and loads packages (dplyr, tidyr, ggplot2, lubridate) and loads the supplier_data.csv dataset.

2. Data Cleaning: Checks the dataset structure, identifies missing values, and detects duplicate invoices.

3. Data Transformation: Converts variables to efficient data types and creates a summary dataset per supplier with metrics like total and average invoice amounts.

4. Descriptive Analysis:
* Summary Statistics
* Outlier Detection (using boxplots and IQR filtering)
* Data Distribution (histogram and density plots)
* Correlation Analysis (total invoices vs. total invoice amount per supplier)
* Categorical Analysis (summary by category and sub-category)
* Trend Analysis (monthly total invoice amounts)

### Usage
1. Install Required R Packages

2. Load the Dataset: Place supplier_data.csv in the project directory and update the file path in the R Markdown file if necessary.

3. Render the R Markdown File: Open the .Rmd file in RStudio and click Knit to generate the HTML output.
