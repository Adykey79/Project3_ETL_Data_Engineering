# Project 3 - ETL and Data Engineering
---
**Brief Description**: This project applies basic ETL and Data Engineering principles to perform a cursory stock analysis of a small portfolio of five stocks:
> - *Part 1: Database Design* - ETL workflows are used to ingest the data and transform it prior to loading into a database (SQLite).
> - *Part 2: Data and Delivery* - The data is read from the database created in the above step and visualized using Pandas Dataframe.<br>

**Inputs**: The project uses the following new libraries at various stages for the analysis:
> - *yfinance* - Python library to seamlessly retrieve stock data from Yahoo Finance. It is a Python API to the Yahoo Finance site.
> - *plotly express* - Built-in as part of the Plotly library that uses graph objects and can create entire figures at once.
> - *Stock Portfolio* - The project uses a small sample of five large-cap stocks (Microsoft, Google, Apple, Intel and Oracle) for this analysis. <br>

**Outputs**: The following outputs are provided at different stages of this project:
> - *Part 1: Database Design*: A detailed ETL workflow of the transformed data including the related ER diagram using QuickDBD is generated.    
> - *Part 2: Data and Delivery*: Specific candle plots and scatter bubble plots that visualize the pricing trends of the stocks in the portfolio.  
> - *Popups*: Popups that provide additional information about the specific price point when clicked.<br>

**References**:
> - Plotly Express Reference Guide, https://plotly.com/python/plotly-express/ accessed April 2024.
> - Pandas Datareader for Yahoo, https://pandas-datareader.readthedocs.io/en/latest/remote_data.html#remote-data-yahoo, accessed April 2024.
> - Bubble Charts using Plotly, https://plotly.com/python/bubble-charts/, accessed April 2024. 
