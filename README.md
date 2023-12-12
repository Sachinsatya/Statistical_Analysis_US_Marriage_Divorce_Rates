[![MasterHead](https://github.com/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates/blob/main/us2.jpg)](https://dharamdudi.github.io)
![GitHub language count](https://img.shields.io/github/languages/count/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates)
![GitHub top language](https://img.shields.io/github/languages/top/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates)
![GitHub watchers](https://img.shields.io/github/watchers/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates)
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates)
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates)

# Statistical Analysis of US Marriage & Divorce Rates
In this project, I have performed statistical analysis on the marriage and divorce rates of states of USA.

The dataset contains the marriage and divorce rates of the years 1990, 1995 and 1999-2021. The dataset is downloaded from the following link: 
[https://www.cdc.gov/nchs/nvss/marriage-divorce.htm](https://www.cdc.gov/nchs/nvss/marriage-divorce.htm)

The notebook of the statistical analysis can be viewed at [stats_analysis.py](https://nbviewer.org/github/dharamdudi/Statistical_Analysis_US_Marriage_Divorce_Rates/blob/main/stats_analysis.ipynb)

## Research Statement
Find out whether the marriage rate and divorce rate in the states of USA have declined across the years. Examine any relation (if exists) between both the rates in various states.

## Data Preparation
After collecting the data, found the following issues:
- Irrelevant records - Deleted the irrelevant records
- Missing values - Filled the missing values of both rates by the median of the respective rate.
- Irregular index and column names - Changed the index names and also the column names.

## Research Answer
- The marriage and divorce rates over the years have declined with a steep decline in the year of 2019 (courtesy of Covid19).
- Both marriage and divorce rates are significantly correlated in most of the states.
