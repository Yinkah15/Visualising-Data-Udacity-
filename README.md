# Exploring Loan Data from Prosper
## (by Ibiyinka Daramola)


## Dataset

This data set contains 113,937 loans with 81 variables on each loan from a loan company called Prosper. The variables include loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) to understand the dataset's variables.

- Since there quite a number of variables, certain variables of interest would be selected to create a smaller dataset and then explored
- Out of the 81 variables, 15 of interest were selected and used for analysis
- Preliminary wrangling involved: 
                Selecting only few relevant columns
                Adjusting data types
                Specifically changing IncomeRange and Prosper score to Ordered Categorical Datatype
## Project Files
The project files contain:
1) Jupyter notebook and html files of step-by-step sourcing, wrangling , analysis and visualisation of the data (Part_I_Prosper_Loan_Exploration.ipynb/html)
2) A short presentation of the key insights through visualisations (Part_II_Prosper_Loan_slide_deck.ipynb)

## Summary of Findings

In summary, income range and prosperscore seem to have a notable influence on the BorrowerAPR and Loan Amount taken ; with higher income ranges and prosperscores being related to hihger Loan Amounts and lower BorrowerAPR
Other findings are listed as below:
There are 3 distinct terms of 36 months, 60 months and 12 months
Over 75% of the loans were of 36 months tenure
About 50% of the loans were still running (Current) at that point and about 33% were already completed
One of the important numerical variables is the BorrowerAPR, an histogram of this variable revealed a roughly normal distribution with some  outliers
Another numerical variable of interest is the LoanOriginalAmount. An histogram of this showed a skewness of the data to the right. It also revealed notable peaks at certain intervals suggestive that standard loan amounts are ususally given which are sometimes varied.
All loans with available Prosperscores had a normal distribution
Most loans were taken by employed people and homeowners
Most loans were taken by earners within the $25,000-49,999 and $50,000-69,999 ranges
BorrowerAPR falls with increasing income and prosper score
LoanOriginalAmount increases with increasing incomerange and Prosperscore

## Key Insights for Presentation

For the presentation, I'll focus on the major influences on BorrowerAPR and LoanOriginalAmount
I'll start by giving a brief overview of the dataset.
The key insights will then be presented with bullet points and the relevant charts

The violin plots and scatter plots showing these would be presented:
BorrowerAPR falls with increasing income and prosper score
LoanOriginalAmount increases with increasing incomerange and Prosperscore
