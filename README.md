# The Impact of COVID-19 on the Stock Market

## Introduction
In the project, explored the relationship between COVID-19 and the stock market, analyzing the impact of the pandemic on financial markets. Utilizing the concepts and skills to create visualizations and reports that showcase the effects of COVID-19 on stock prices. The global outbreak of the virus has caused significant disruptions, leading to fluctuations in stock markets worldwide. By examining this relationship, seek to gain insights into the intricate dynamics at play and demonstrate the proficiency in data visualization and analysis. This project aims to contribute to the understanding of how COVID-19 has influenced the stock market while showcasing the practical application of learned concepts.

## Methodology
- Importing Data with Pandas
Read the daily confirmed cases and deaths into two data frames, and the link can be found on this GitHub: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv


- Use AlphaVantage (the stock API used earlier in the course) to get the daily high and low prices for selected stocks

    **Create 5 stock markets' data frame**

    a) Overall American Market: American S&P 500 Index

    b) Overall Canadian Market: Canadian iShares S&P/TSX 60 Index Fund

    c) Travel sector: Alimentation Couche-Tard (TSE:ATD.TO)

    d) The Real Estate sector: iShares Global Real Estate Index ETF

    e) Precious metals (Gold, Silver, Platinum, etc): iShares S&P/TSX Global Gold Index ETF

    Because this API key could not fetch the daily data of the stock market which is a premium endpoint, only fetched the weekly data.

- Cleaning Data

- Exploring Data

- Visualizing with Matplotlib

## Conclusion

- Used the line chart with different y axes to visualize the USA and Canada's COVID-19 Confirmed Cases and Death Cases trend. Because the line graph can better show the relationship between time and epidemic change. Different y axes can more clearly show the trend of Confirmed Cases and Death Cases in the two countries, eliminating the influence of the size of the number on the trend.

- Used the line chart with different y axes to visualize the USA and Canada's stock market in one figure, and in another figure to display the travel, real estate, and precious metals market trend. The same reason as COVID-19.

- Over all, the impact of COVID-19 in the USA and Canada on all 5 stock markets coincided with the timing.
