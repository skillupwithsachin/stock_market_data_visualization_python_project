# stock_market_data_visualization_python_project

There are various data visualization libraries available in Python. The top five are shown below:

Matplotlib
Pandas
NumPy
Plotly Express
Seaborn
For this project, we’ll use Matplotlib in combination with the Pandas library.

We can use stock market data for educational, business, and even personal interests. All data sets are at a day-level, with pricing and trading values split across them. There are CSV files for each stock and a metadata file with some macro-information about the stocks themselves. The data spans from the 26th of May, 2008 to the 30th of April, 2021. Since new stock market data is generated each day, the data set will be updated monthly for the latest and most helpful information.

We’ll load the data and examine its header. In the dataset:

The “High” column represents the highest price in a day.
The “Low” column represents the lowest price in a day.
The “VWAP” column represents the volume-weighted average price.
The “Volume” column represents the volume of the data.


We’ll now preprocess the data to make later analysis easier. For this, set the “Date” column as an index. This will make it bold-faced.

Then, filter the dates from 2008-05-26 to 2021-04-30. We can now convert an index to an ordinary column of the data frame.

Plot the volume of each day by using the Seaborn and plotly.express library.

Plot the highest price for each day using the plotly.express library.

In a moving average, we consider a subset of data and calculate its average. In stock market analysis, the moving average smooths out short-term price fluctuations, and filters out the noise (outlier data that could confuse the model). This results in a clearer picture of the price trend as compared to the raw data.

The measure of autocorrelation represents the relationship between the current value of a variable with its past value. We can use it to check whether the elements in the time series data are positively correlated, negatively correlated, or independent of each other.

Heat maps use colored cells at different time frames to represent the intensity of the first variable of interest, such as price, temperature, rainfall, and so on. In this plot, analyze the prices of the stock at different time frames.
