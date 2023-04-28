# The Impact of COVID-19 on the Stock Market
link: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

## Read the daily confirmed cases and deaths into two data frames can be found on this GitHub
## Use pandas to create a data frame that aggregates and sums both confirmed cases and deaths on a global level
- NumPy
- Pandas
### Use AlphaVantage (the stock API used earlier in the course) to get the daily high and low prices for your selected stocks
Create 5 stock markets' data frame
a) Overall American Market: American S&P 500 Index

b) Overall Canadian Market: Canadian iShares S&P/TSX 60 Index Fund

c) Travel sector: Alimentation Couche-Tard (TSE:ATD.TO)

d) The Real Estate sector: iShares Global Real Estate Index ETF

e) Precious metals (Gold, Silver, Platinum, etc): iShares S&P/TSX Global Gold Index ETF

Because this API key could not fetch the daily data of the stock market which is a premium endpoint, we fetch the weekly data.


- Matplotlib

## Research a stock for each below that reflects the following industries
- What was the COVID-19 impact on the price of the stock over time?

- What was the correlation between different stocks' closing prices?

## This Notebook will Show Use of:

- Importing Data with Pandas
- Cleaning Data
- Exploring Data through Visualizations with Matplotlib

## Conclusion

- Used the line chart with different y axes to visualize the USA and Canada's COVID-19 Confirmed Cases and Death Cases trend. Because the line graph can better show the relationship between time and epidemic change. Different y axes can more clearly show the trend of Confirmed Cases and Death Cases in the two countries, eliminating the influence of the size of the number on the trend.

- Used the line chart with different y axes to visualize the USA and Canada's stock market in one figure, and in another figure to display the travel, real estate, and precious metals market trend. The same reason as COVID-19.

- To better compare the impact of COVID-19 on the stock market, we only took the data from the period when COVID-19 occurred to show the stock market changes. Those two countries have a similar trend in the stock market.

- Over all, the impact of COVID-19 in the USA and Canada on all 5 stock markets coincided with the timing.
