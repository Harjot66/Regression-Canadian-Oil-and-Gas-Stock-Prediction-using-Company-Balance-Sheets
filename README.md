# Regression: Canadian Oil and Gas Stock Price Prediction using Company Balance Sheets

### Introduction

In this project we want to create a stock price prediction model using company balance sheet values for various Canadian oil and gas companies. We will be using the Python Yahoo Finance API to get the data, then we would be utilizing Python for data wrangling and cleaning, then we would switch into R, where we would go ahead and attempt to create a powerful regression model to predict the stock price off of a given oil and gas company's balance sheet values. From my accounting knowledge, it was decided that utilizing a balance sheet for stock price prediction would make the most sense as this is the one company financial statement which provides a snapshot in time, whereas other financial statements provide values over a certain period of time. This regression model would then be able to be used for a strategy of value investing within the oil and gas industry.

Value Investing: An investment strategy based on looking for stocks which are undervalued by the market at large.

### Dataset:

Date

Ordinary Shares Number

Share Issued

Net Debt

Total Debt

Tangible Book Value

Invested Capital

Working Capital

Net Tangible Assets

Common Stock Equity

Total Capitalization

Total Equity Gross Minority Interest

Stockholders Equity

Capital Stock

Common Stock

Total Liabilities Net Minority Interest

Total Non Current Liabilities Net Minority Interest

Other Non Current Liabilities

Non Current Deferred Liabilities

Non Current Deferred Taxes Liabilities

Long Term Debt And Capital Lease Obligation

Long Term Debt

Current Liabilities

Current Debt And Capital Lease Obligation

Payables And Accrued Expenses

Payables

Accounts Payable

Total Assets

Total Non Current Assets

Other Non Current Assets

Net PPE

Current Assets

Inventory

Receivables

Accounts Receivable

Cash Cash Equivalents And Short Term Investments

Cash And Cash Equivalents

Stock Price

Stock Ticker

### Results

In summarizing the project, we encountered challenges in constructing a robust regression model. These challenges included a scarcity of strong variable predictors and difficulties in meeting various regression model assumptions, both before and after applying a Box-Cox transformation. Notably, our findings indicate that company balance sheets lack efficacy as predictors for the closing stock prices of Canadian oil and gas companies. This limitation arises from the fact that most balance sheet values exhibit an insignificant relationship with the closing stock price. Additionally, those few balance sheet values that do demonstrate a significant relationship fail to satisfy fundamental regression requirements such as the equal variance and normality of residuals assumptions, rendering the model unsuitable for predictive purposes. These insights underscore the importance of exploring factors beyond financial statement values when evaluating potential investments in the oil and gas sector. Investors are encouraged to delve deeper into a company's mission statement, social media activity, management history, and other non-financial aspects to make more informed investing decisions.

### Conclusion

In conclusion, it appears that balance sheets may not be a reliable predictor for the closing stock prices of Canadian oil and gas companies. This is likely due to the influence of extraneous factors beyond the numerical values presented in financial statements that significantly impact the closing stock prices.

### References

Yfinance. PyPI. (2023). https://pypi.org/project/yfinance/
