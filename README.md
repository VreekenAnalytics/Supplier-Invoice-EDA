# Supplier-Invoice-EDA

### Overview
This repository contains an Exploratory Data Analysis (EDA) of supplier invoices, aimed at uncovering insights into supplier relationships, invoice volumes, and spending patterns within a supply chain context. The analysis was conducted in R and presented in an R Markdown file, with HTML output for easy viewing.

### Contents
* Supplier_Invoice_EDA.Rmd: The R Markdown file containing the full EDA, including data cleaning, transformation, and visualization.
* Supplier_Invoice_EDA.html: The HTML output generated from the R Markdown file, providing a convenient way to view the analysis results.
* README.md: This document, providing an overview of the project and instructions for using the files.

### Purpose of the Analysis
The objective of this EDA is to provide insights for procurement management.

### Analysis Structure
The analysis consists of the following sections:

#### Preparing Environment:

* The required R packages (dplyr, tidyr, ggplot2, lubridate) are installed and loaded.
* The dataset supplier_data.csv is loaded, which contains sample data on supplier invoices.

### Data Cleaning:

* The dataset is examined for structure, missing values, and duplicate invoices to ensure data quality.

#### Data Transformation:

* Key variables are transformed into appropriate data types.
* A summary dataset is created, grouping by supplier and calculating total, average, and count of invoices per supplier.

### Descriptive Analysis:

* Summary Statistics: Provides basic statistics on invoice amounts, total invoices, and suppliers.
* Outlier Detection: Boxplots and IQR-based filtering are used to identify outliers in invoice amounts and total invoices per supplier.
* Data Distribution: Histogram and density plots visualize the distribution of invoice amounts.
* Correlation Analysis: Scatter plots reveal correlations between total invoice amounts and the number of invoices per supplier.
* Categorical Analysis: Summary statistics are calculated per category and sub-category of suppliers.
* Trend Analysis: A time series analysis of total invoice amounts per month, visualized with line plots.

### Usage and Reproduction
To run the analysis and reproduce the results:

* Install Required R Packages: Open the R Markdown file (Supplier_Invoice_EDA.Rmd) in RStudio and make sure the following packages are installed:
* Load the Dataset: Ensure that the supplier_data.csv dataset is available in the project directory. Update the file path in the R Markdown file if necessary.
* Render the R Markdown File: Open the .Rmd file in RStudio and click on Knit to generate the analysis output in HTML format.
