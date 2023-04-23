# The Impact of COVID-19 on the Stock Market

Stock-Market-Analysis
Stock Market Analysis and Prediction is the project on technical analysis, visualization, and prediction using data provided by AlphaVantage. By looking at data from the stock market, particularly some giant technology stocks and others. Used pandas to get stock information, visualized different aspects of it, and finally looked at a few ways of analyzing the risk of a stock, based on its previous performance history. Predicted future stock prices through a Monte Carlo method!

Dependencies:
NumPy
IPython
Pandas
Matplotlib
Seaborn
Goal Of The Notebook
The purpose of this project is to comparatively analyze the effectiveness of prediction algorithms on stock market data and get general insight on this data through visualization to predict future stock behavior and value at risk for each stock. The project encompasses the concept of Data Mining and Statistics. This project makes heavy use of NumPy, Pandas, and Data Visualization Libraries.

Queries Answered
What was the change in price of the stock over time?
What was the daily return of the stock on average?
What was the moving average of the various stocks?
What was the correlation between different stocks' closing prices?
What was the correlation between different stocks' daily returns?
How much value do we put at risk by investing in a particular stock?
How can we attempt to predict future stock behavior
This Notebook will Show Use of:
Data Mining
Data Handling
Importing Data with Pandas
Cleaning Data
Exploring Data through Visualizations with Matplotlib
Barplots
KDE-Plots
lmplots
Heatmap


# Conclusion

7.6.1  We use the line chart with different y axes to visualize the USA and Canada's COVID-19 Confirmed Cases and Death Cases trend. Because the line graph can better show the relationship between time and epidemic change. Different y axes can more clearly show the trend of Confirmed Cases and Death Cases in the two countries, eliminating the influence of the size of the number on the trend.

7.6.1.1  Confirmed or Death Cases in the USA are depicted by the blue line, while those in Canada are represented by the red line from Jan. 2020 to Dec. 2022. Those two countries have a similar trend of COVID-19 Confirmed Cases or Death Cases change.

7.6.1.2  Confirmed Cases: Slightly started increasing steadily from the early period of 2020. There were two periods of sharply increasing trend, one is from Nov. 2020 to Feb. 2021, and the other is from Jan. to Feb. 2022. The latter is more intense.

7.6.1.3  Death Cases: Deaths in USA and Canada have been relatively stable relative to diagnoses, while deaths in Canada have been more stable and more in a straight line than in the USA. The increase in deaths in these two countries was not caused by a sudden increase in confirmation.

7.6.2  We use the line chart with different y axes to visualize the USA and Canada's stock market in one figure, and in another figure to display the travel, real estate, and precious metals market trend. The same reason as COVID-19.

7.6.2.1  To better compare the impact of COVID-19 on the stock market, we only took the data from the period when COVID-19 occurred to show the stock market changes. Those two countries have a similar trend in the stock market.

7.6.2.2  The outbreak began in North America in Feb. 2020, sending U.S. and Canadian stock markets tumbling to three-year lows in Apr. 2020. After that, the stock market rose steadily until Jan. 2022. We can see very clearly from the time series chart that the two periods of sharply increasing of confirmed cases had a huge impact on the USA and Canada’s stock markets. After that, the two stock markets started to move down again, rebounded slightly, and reached the height of January in April, but then continued to fall, forming a W bottom. By December they were still rebounding but had not regained their Jan. 2022 heights.

7.6.2.3  Travel (green line), real estate (black line), and precious metals (yellow line) markets were effect by the COVID-19 pandemic too. The same with the stock market, in the early days of COVID-19, these three markets also had a certain impact from Feb. 2020 to the lowest point in Apr. 2020.

The travel market rebound afterward. But the plunge was triggered by the first sharp spike in COVID-19 confirmation from Nov. 2020 to Feb. 2021. Since then, it has been a wave up to its highest point.

The real estate market fluctuated at a low level and gradually rose from Apr. 2021 to Feb. 2022. It began a wave decline and is now at a three-year low.

Until Apr. 2022, the precious metals and real estate markets had moved in almost the opposite direction. Since then, it has fluctuated and is now low.

7.6.3  In short, the impact of COVID-19 in the USA and Canada on all 5 stock markets coincided with the timing.
