This project is a simple exploratory data analysis of stock prices.

We use pandas datareader to get stock information for the following banks from Yahoo Finance for the time period Jan 1st 2006 to Jan 1st 2016:

Bank of America<br />
CitiGroup<br />
Goldman Sachs<br />
JPMorgan Chase<br />
Morgan Stanley<br />
Wells Fargo<br />

The data for each bank is stored in a separate dataframe and then concatenated.

Since the time period includes the financial crisis of 2008, the visualizations clearly show the crash of stock prices especially in the case of CitiGroup and Goldman Sachs. We plot the close prices against the rolling average to get a clear picture of performance. Heatmaps show the correlation between the banks' returns.
