# Unit 4 Initial Analysis and Custom Portfolio Analysis

## Quantitative Analysis of Initial Portfolios

* Performance Analysis 
1. Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?

Yes, all portfolios had cumulative returns that out performed the S&P. 

![Cumulative Returns](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\cumulative returns.PNG)

* Risk Analysis
1.  Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?

 For daily returns, the largest spread was Tiger Global Management. 

![Box Plot Daily Returns](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\boxplot_returns.PNG)

Note - For somereason 'PAULSON & CO.INC.' would not be allowed in the boxplot formula. I tried different spellings like PAULSON & CO. INC. , PAULSON & COINC., ETC. Paulson & Son is included in every other calculation. 

2. Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?

Berkshire Hathaway and Tiger Global Management LLC.

* Rolling Statistics


1. Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does the risk increase for each of the portfolios at the same time risk increases in the S&P?

Using a 21 day rolling standard deviation, it appears the STD of the SP500 mirrors the others. 

![Line Plot](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\std_returns.PNG)

2. Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?

Using a 21 day rolling standard deviation, Soros Fund is highly correletive to the SP 500.  

![Table](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\corrtable.PNG)

3. Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?

Using 60 daily rolling average for daily returns, no the two do not seem correlated. 

![BETA](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\BETA.PNG)


* Plot Sharpe Ratios

1. Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.

![Sharpe](C:\Users\johnh\Desktop\PREWORK_JSH\Module-3\PORTFOLIO_HW\Unit4-A-Whale-Off-the-Port-folio-\sharpe.PNG)

2. Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.

In this case, the S&P 500 daily returns had significantly lower Sharpe Ratios than the others, ALGO 1 was the highest Sharpe Ratio, indicating their portfolio risk levels were optimized for performance. 

## Create Custom Portfolio
Harold is ecstatic that you were able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales portfolios. However, now you are wondering whether you can choose your own portfolio that performs just as well as the algorithmic portfolios. 

* I chose QIWI,WING,and DIS. 

* Risk:
 