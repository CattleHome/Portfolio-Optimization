# Portfolio-Optimization

As part of an assignment in a course called Asset Pricing, we were tasked to plot a minimum-variance frontier of 10 industry portfolios with tangency portfolio & determine the weights of the industry portfolios at tangency portfolio.

## Task at hand

Industry_Portfolios.xlsx contains monthly nominal (net) returns for ten industry portfolios, expresssed as a percentage. i.	These returns cover the ten-year period from Jan 2004 through Dec 2013. 

1. Calculate the vector of mean returns and covariance matrix of returns for the ten industry portfolios.
2. Use this to plot the minimum-variance frontier generated by the ten industry portfolios, with mean return on the y axis and standard deviation of return on the x axis. The plot should cover the range from 0% to 2% per month on the y axis.
3. Now suppose that the riskless asset offers risk-free return of 0.13% per month. Plot the efficient frontier (with the riskless asset) on the same plot as the minimum-variance frontier generated by the ten industry portfolios.
4. Calculate the weights of the ten industry portfolios at the tangency portfolio.


### Definitions & Economic Significance

Minimum-variance frontier: the minimum-variance frontier consists of portfolios with lowest risk for given mean return. Hence no portfolio can lie outside (i.e. to the left) of the minimum-variance frontier.

Efficient frontier: the efficient frontier consists of portfolios with highest mean return for given risk. Hence rational risk-averse investors will choose to hold optimal portfolio that lies on the efficient frontier.

Tangency portfolio: Tangency portfolio is risky portfolio with highest Sharpe ratio. Hence if all investors are rational and risk-averse, then the tangency portfolio will be the market portfolio. 

### Prerequisites

The code is carried out on Jupyter Notebook using Python 3.6. Most libraries imported in this code comes together with Anaconda.

### Break down of code

1. Parsing the excel file of the 10 Industry portfolios
2. Calculate vector of mean returns & covariance matrix of returns
3. Determine Lagrange multipliers e.g. alpha, delta, zeta
4. Provide evenly-spaced values for plot of Minimum-Variance portfolio
5. Determine mean, variance and weights of Minimum-Variance portfolio
6. Determine expected return, variance and weights of Tangency portfolio
7. Plot the Minimum Frontier portfolio with Tangency portfolio
