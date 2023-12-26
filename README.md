# quant_ml_nifty50
**Project  - Unsupervised Learning Trading Strategy **

﻿1. Download NIFTY 50 stocks prices data.
   
2.Calculate different technical indicators and features for each stock.

3.Aggregate on monthly level and filter for each month only top 10 most liquid stocks. Calculate monthly returns for different time-horizons to add to features.

4.Download Fama-French Factors and calculate rolling factor betas for each stock.

5.For each month fit a K-means clustering model to group similar assets based on their features.

6.For each month select assets based on the cluster and form a portfolio based on Efficient Frontier max sharpe ratio portfolio optimization.

7.Visualize the portfolio returns and compare to NIFTY 50 returns.



! Limitation! We are going to use most recent  NIfty 50 stocks list, which means that there may
be a survivorship bias in this list, in reality you have to use survivorship free data.
