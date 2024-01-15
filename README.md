# Regression: Canadian Oil and Gas Stock Price Prediction using Company Balance Sheets

### Introduction

In this project we want to create a stock price prediction model using company balance sheet values for various Canadian oil and gas companies. We will be using the Financial Modelling Prep (Financial Modelling Prep, 2024) and Python Yahoo Finance (Yfinance PyPI., 2023) API's to gather the data, then we would be utilizing Python for data wrangling and cleaning, then we would switch into R, where we would go ahead and attempt to create a robust regression model to predict the stock price off of a given oil and gas company's balance sheet values. From my accounting knowledge, it was decided that utilizing a balance sheet for stock price prediction would make the most sense as this is the one company financial statement which provides a snapshot in time, whereas other financial statements provide values over a certain period of time. This regression model would then be able to be used as a strategy of value investing within the Canadian oil and gas industry.

Value Investing: An investment strategy based on looking for stocks which are undervalued by the market at large.

### Dataset:

date

cashAndCashEquivalents

shortTermInvestments

cashAndShortTermInvestments

netReceivables

inventory

otherCurrentAssets

totalCurrentAssets

propertyPlantEquipmentNet

goodwill

intangibleAssets

goodwillAndIntangibleAssets

longTermInvestments

taxAssets

otherNonCurrentAssets

totalNonCurrentAssets

otherAssets

totalAssets

accountPayables

shortTermDebt

taxPayables

deferredRevenue

otherCurrentLiabilities

totalCurrentLiabilities

longTermDebt

deferredRevenueNonCurrent

deferredTaxLiabilitiesNonCurrent

otherNonCurrentLiabilities

totalNonCurrentLiabilities

otherLiabilities

capitalLeaseObligations

totalLiabilities

preferredStock

commonStock

retainedEarnings

accumulatedOtherComprehensiveIncomeLoss

othertotalStockholdersEquity

totalStockholdersEquity

totalEquity

totalLiabilitiesAndStockholdersEquity

minorityInterest

totalLiabilitiesAndTotalEquity

totalInvestments

totalDebt

netDebt

ClosingStockPrice

### Results

In summarizing the project, we encountered challenges in constructing a robust regression model. These challenges included a scarcity of strong variable predictors and difficulties in meeting various regression model assumptions, both before and after applying a Box-Cox transformation. Notably, our findings indicate that company balance sheets lack efficacy as predictors for the closing stock prices of Canadian oil and gas companies. This limitation arises from the fact that most balance sheet values exhibit an insignificant relationship with the closing stock price. Additionally, those few balance sheet values that do demonstrate a significant relationship fail to satisfy fundamental regression requirements such as the equal variance and normality of residuals assumptions, rendering the model unsuitable for predictive purposes. These insights underscore the importance of exploring factors beyond financial statement values when evaluating potential investments in the oil and gas sector. Investors are encouraged to delve deeper into a company's mission statement, social media activity, management history, and other non-financial aspects to make more informed investing decisions.

### Conclusion

In conclusion, it appears that balance sheets may not be a reliable predictor for the closing stock prices of Canadian oil and gas companies. This is likely due to the influence of extraneous factors beyond the numerical values presented in financial statements that significantly impact the closing stock prices.

### References

Bank of Canada (2024), Daily Exchange rates, https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates/

Bank of Canada (2022), Daily Exchange rates: Lookup tool, https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates-lookup/?lookupPage=lookup_daily_exchange_rates_2017.php&startRange=2017-01-01&series%5B%5D=FXUSDCAD&lookupPage=lookup_daily_exchange_rates_2017.php&startRange=2017-01-01&rangeType=range&rangeValue=&dFrom=2022-12-29&dTo=2023-01-01&submit_button=Submit

Caplinger, D. (2023). The basics of value investing strategy. The Motley Fool. https://www.fool.com/investing/stock-market/types-of-stocks/value-stocks/value-investing-guide/#:~:text=Value%20investing%20is%20an%20investment,and%20earnings%20from%20their%20businesses. 

Financial Modelling Prep (2024), Free stock market API and financial statements API, https://site.financialmodelingprep.com/developer/docs

Yfinance. PyPI. (2023). https://pypi.org/project/yfinance/
