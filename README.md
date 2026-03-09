# gold-market-analysis-python
Exploratory data analysis and machine learning project analyzing gold price behavior using financial market data.

# Gold Market Analysis Using Python

## Overview
This project explores historical gold price behavior using financial market data. The goal of the analysis was to investigate relationships between gold and several other financial indicators and experiment with predictive models that attempt to forecast gold price direction.

The project was completed as part of my DSC 530 coursework in applied statistics and data analysis.

## Dataset
The dataset contains historical financial market data including:

• Gold prices (GLD)  
• S&P 500 index values  
• Oil prices  
• Silver prices  
• EUR/USD exchange rate  

The dataset used in this analysis can be found in the **data** folder.

## Tools Used
Python  
Pandas  
NumPy  
Matplotlib  
Scikit-learn  

## Project Workflow

### Data Preparation
The dataset was loaded and prepared using Python. Financial indicators were cleaned and converted to appropriate formats for time-series analysis. Additional variables such as daily returns and lagged returns were created to analyze price movements.

### Exploratory Data Analysis
Exploratory analysis was performed to understand the statistical properties of gold returns. This included summary statistics, distribution plots, and visualization of market relationships.

### Correlation Analysis
Relationships between gold and other financial indicators such as the S&P 500, oil prices, silver, and EUR/USD were analyzed using correlation analysis.

### Hypothesis Testing
A statistical t-test was conducted to determine whether gold returns were statistically significant.

### Predictive Modeling
Two machine learning models were implemented to explore predictive patterns in gold price movement:

• Logistic Regression  
• Random Forest Classifier  

### Clustering
Clustering techniques were also applied to identify patterns within the financial dataset.

## What I Learned
This project helped me practice applying statistical analysis, exploratory data analysis, and machine learning techniques to financial market data using Python.

It also reinforced how financial indicators can interact and influence market behavior.
