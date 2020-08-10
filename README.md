# 2020 Asset Class Performance
 
### PROJECT SUMMARY ###
This was a quick project to create a visualization of risk and returns of multiple investment 
asset classes over a time period starting on December 31, 2019 and ending on August 7, 2020.

### METHOD OF ANALYSIS ###
ETF Assets were selected as proxies for the asset classes used in the analysis. ETFs were chosen
due to their high liquidity, leading to reliable daily pricing information. Furthermore, the
liquid nature of ETFs allows them to be purchased by any investor, institutional or personal.

The information was gathered from Yahoo! Finance, and saved into a csv file. Additional data cleaning
was performed using excel, capturing stock splits that were apparently missed in the original dataset.

The chart was created using a Python 3.7.6, Pandas 1.0.5, plotly 4.8.2, and plotly-express 0.4.1.