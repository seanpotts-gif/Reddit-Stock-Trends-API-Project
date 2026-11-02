# Reddit-Stock-Trends-API-Project
A small project tracking the top 50 highest performing stocks from r/wallstreetbets. 
Name: Sean Potts
Summary: How has a stocks performance influenced their discussion online over time? This study analyzes the top 50 highest performing stocks that are most commonly talked about on r/wallstreetbets. Its goal is to generate insight into how online discussion might influence the performance of a stock, and whether or not a positive or negative performance impacts stock discussion frequency. 
Data: The data collected is from the Tradestie API which takes publicly available data from Reddit and organizes it under an API. 
Methods: Using a free API key from Tradestie to increase the number of calls per minute to 200, I used python in a Jupyter Notebook kernel to call the data. The data was from a range of about a month from August 1st - September 1st 2026 and I used Pandas to create the call and matplotlib.pyplot to graph my data. 
Findings:
How to Reproduce: You can recreate my same call with the same date ranges by requesting a key from Tradestie and creating a loop that that makes a call for each date in the range. After that, just compile your request into a dataframe and plot with matplotlib. 
