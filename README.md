# Stock-Tracking-Algorithm
Python-built algorithm that that tracks previous fluctuations of Apple stock by pulling data from the Stooq Index Data sheet
implemented with the pandas_datareader library and pushes the calculated future stock pricing data to Twitter using a tweepy API.
The data collected from the Stooq sheet is used to create the algorithm using a series of previous days set by variable amount and epoch
values to generate a graph presenting future predicted values to a degree of roughly 85% accuracy when compared to actual values
of the stock.
