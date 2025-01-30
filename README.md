### Retail Sales Dashboard - Data Visualisation
## Gaining insights about sector performance and consumer demand from retail sales in UK.

The data used for this project (referring to the file poundsdata.xlsx) has been obtained from publicly available data provided by the Office for National Statistics (ONS). This data can be found at https://www.ons.gov.uk/businessindustryandtrade/retailindustry/datasets/poundsdatatotalretailsales.

# Important Notes:
1. *Tools* - The dashboard has been created using PowerBI, raw data has been transformed using Power Query, and both in-built measures and DAX formulas to create the report visualisations.
2. *Data Used: Adjusted vs Non-adjusted* - The provided data can be categorised into two major groups - Seasonally adjusted and Non-seasonally adjusted data. This project used **non-seasonally adjusted** data in order to better understand raw data, as well as the real numbers and estimates. An important note is that calendar and seasonal effects will be expected to incorporated in the yearly totals. 
3. *Data Used: Value vs Volume*: The purpose of this project is to analyse consumer behavior changes across sectors and sector comparison. The project will therefore use **Value** data for sector performance and **Volume** data for consumer behaviour trends, as it removes the effect of inflation and price changes and focuses on products bought/sold.
4. *Time Period* - The data contains different time periods for different sheets, earliest of which is January 1986, and ending December 2024. This project will include the time period of last 10 years for the analysis, i.e. from January 2014 to December 2024, to understand trends and gain insights. An important note is that the time period used should be relevant to current times and trends.

**Based on the above explanations, four subsets of have been used. They are as follows: Value Non-seasonally adjusted - Total Sales, Volume Non-seasonally adjusted - Total Sales, Value Non-seasonally adjusted - Total Sales Detailed Level, Volume Non-seasonally adjusted - Total Sales Detail Level.**

# Glossary of some terms: 
*These glossary terms are interpreted as per the ONS glossary for this dataset.*
1. Value refers to the amount spent in any time period.
2. Volume refers to the quantity bought in any time period - which is the value estimates adjusted to remove the effect of price changes.
3. Non-seasonally adjusted refers to the raw data estimates.
4. Seasonally adjusted refers to the estimates derived by adjusting to remove the effect of seasonal changes and calendar effects such as Easter or Christmas.

