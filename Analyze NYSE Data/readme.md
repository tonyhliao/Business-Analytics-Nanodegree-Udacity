# Analyze NYSE Data
## Introduction 
In this project, I analyzed real-life data from the New York Stock Exchange. Udacity provided a subset of a dataset from Kaggle, which contains historical financial data from S&P 500 companies. This data subset can be found <a href="https://github.com/tonyhliao/Business-Analytics-Nanodegree-Udacity/blob/main/Analyze%20NYSE%20Data/Original%20Dataset.csv">here</a>.

## Part 1: Summary Statistics and Industry Comparison
In order to determine whether the companies in the Semiconductor industry had similar Operating Profits compared to those in the Aerospace & Defense industry, the Gross Profit and Operating Profit had to be calculated from the dataset. 

Gross Profit = 'Total Revenue' - 'Cost of Goods Sold'\
Operating Profit = 'Gross Profit' -  'Sales, General and Admin.' - 'Research and Development' - 'Other Operating Items'

After calculating these two metrics and filtering the data, the summary statistics for both industries are as follows:
![image](https://user-images.githubusercontent.com/79599703/113601696-49adda80-9607-11eb-83fe-d683446870e6.png)

My analysis and visual chart showing the operating profits of both industries:
![image](https://user-images.githubusercontent.com/79599703/113607125-787b7f00-960e-11eb-87b3-922d494bbfbb.png)

<i>Note: For the interactive versions of Part 2 and 3, as well as the Pivot Table, Filtered Data, and other spreadsheets used in Part 1, download the final Excel workbook <a href="https://github.com/tonyhliao/Business-Analytics-Nanodegree-Udacity/blob/main/Analyze%20NYSE%20Data/Original%20Dataset.csv">here</a>.

## Part 2: Dynamic Profit & Loss Statement
An interactive spreadsheet where the user can pull P&L Statements for different companies.\
<i>One company's P&L Statement:</i>
![image](https://user-images.githubusercontent.com/79599703/113608886-bc6f8380-9610-11eb-828a-a6c914f978a4.png)

## Part 3: Dynamic Forecasting Model
An interactive spreadsheet where the user can choose different operating scenarios for the company 'LUV'. \
<i>The 'base case' scenario:</i>
![image](https://user-images.githubusercontent.com/79599703/113609780-e07f9480-9611-11eb-93c3-e9bbabe6ccc3.png)
