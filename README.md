Portfolio Risk Analysis and Stress Testing Using Value-at-Risk (VaR) and Monte Carlo Simulation
Introduction

In modern financial risk management, it is crucial to understand the potential losses a portfolio might face under different market conditions. This project focuses on analyzing the risk profile of a diversified equity portfolio by applying quantitative techniques commonly used in the finance industry. The primary aim is to estimate the portfolio’s exposure to market risk through Value-at-Risk (VaR) and to evaluate its resilience during extreme market scenarios through stress testing. Together, these tools provide a comprehensive view of both expected and unexpected risks, helping investors and risk managers make informed decisions.

Data Collection and Portfolio Construction

The project begins with the collection of historical stock price data for a selection of ten major publicly traded companies from different sectors. The data spans several years and is adjusted for corporate actions such as dividends and stock splits to ensure accuracy. By choosing companies across various industries, the portfolio achieves diversification, reducing unsystematic risk.

Once the data is collected, daily returns for each stock are calculated, and a portfolio is constructed by assigning predefined weights to each asset. These weights represent the proportion of total capital invested in each stock and sum to one. The overall portfolio return is then derived as a weighted average of the individual asset returns, forming the foundation for subsequent risk calculations.

Value-at-Risk (VaR) Methodology

The core of the analysis involves calculating Value-at-Risk, a widely recognized measure that estimates the maximum potential loss a portfolio could experience over a given time period at a specified confidence level. Three approaches are used to provide a comprehensive perspective:

Historical Simulation: This method uses actual historical return data to estimate potential losses, making no assumptions about the underlying distribution.

Parametric (Normal Distribution) Approach: This technique assumes that returns follow a normal distribution and uses statistical measures such as mean and standard deviation to calculate VaR.

Monte Carlo Simulation: This method involves generating a large number of hypothetical return scenarios based on statistical characteristics of the portfolio to estimate potential losses.

By employing all three methods, the project highlights different ways of quantifying risk — from purely empirical analysis to model-based and simulation-driven approaches.

Stress Testing

While VaR is a powerful tool for estimating potential losses under normal market conditions, it does not capture extreme, low-probability events. To address this limitation, the project incorporates stress testing, which evaluates portfolio performance under adverse market scenarios. Two types of scenarios are considered: a historical period of significant market turbulence and a hypothetical shock affecting all portfolio components simultaneously. This step allows for a deeper understanding of how the portfolio might behave under conditions that go beyond standard risk assumptions.

Conclusion

This project provides a structured approach to portfolio risk management by combining multiple VaR methodologies with stress testing. The integration of historical data analysis, statistical modeling, and simulation techniques allows for a more complete understanding of potential losses and risk exposures. Moreover, stress testing extends this analysis by exploring how the portfolio could respond to rare but impactful events. Together, these tools offer valuable insights for investors, financial analysts, and risk managers seeking to enhance decision-making, optimize asset allocation, and strengthen financial resilience in an uncertain market environment.
