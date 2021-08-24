# HDFC_Internship
This repository consists of all files related to internship at HDFC Bank. The bank statistics data were taken from official Reserve Bank of India website (https://rbi.org.in/Scripts/Statistics.aspx). The data consists of the Point of Sales Machine transaction and ATM transactions for the years 2018 - 2019 (month of May). The objective of this project work was to analyze the **performance** of the Indian banking system.
> Data was segregated into government and private bank datasets
> Feature Engineering was implemented and certain statistics were extracted from the dataset: like per transaction value of credit cards for a particular bank
## Project Details:
**Version:**  Jupyter Notebook 
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, json  

## Data Cleaning
After reading the data, I needed to clean it up so that it was usable for further analysis. I made the following changes and created the following variables:

*	Segregated the bank dataset into Private and Government Banks
*	Parsed numeric data out of ATM and POS transactions 
*	Made columns for transaction value for CC and DC transactions 
*	Removed rows without any transaction values
*	Parsed rating out of company text 
*	Used outstanding CC and DC to aggregate transaction values 
*	Made columns if transaction levels were higher than the average:
    * Credit Cards: Private and Government
    * Debit Cards: Private and Government    
 
## Exploratory Data analysis
Distributions of the data and the value counts for the various categorical variables.Also, data was sorted according to various peaks. 
**Binning Data**: Data was binned according to various categories and then the top performing banks were visualized.

## Data Visualization 
In this step, I created a different jupyter notebook file wherein different visuals of the data are taken into cognizance. It gives an in-depth research of other factors as well which are not present in the primary file such as violin plots, join plots of various categorical features.  

