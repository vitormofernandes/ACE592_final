# ACE592 - Data Science for Applied Economics
#Group 1: Vitor Fernandes, Henrique Monaco, Allie Elmore, Isaac Werries

Spring 2021

The idea of this project is applying sentiment analysis to Twitter data in order to build a portfolio of stocks and compare its performance to traditional market benchmarks. We used Twitter's API to scrape a maximum of 3,000 tweets from 30 relevant Fintwit accounts for the last year. We used stocks who compose the S&P 500 index, whose ticker was mentioned on those tweets and whose average sentiment score for the month was positive to build a weighed portfolio. We rebalance the portfolio every month. After doing the analysis for 12 months, we compare the results to a series of benchmarks. Although we didn't beat the market, we closely tracked the S&P 500 index.

This repo consists of:
1 Jupiter notebook
	Code (Python v 3.9.0) with comments and relevant figures
1 PDF
	Final write-up for the project
1 xlsx spreadsheet
	Excel spreadsheet containing the scraped tweets and their respective user, location and date-time of creation

