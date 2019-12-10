# Markowitz_Frontier
A simulation of Markowitz Efficient Frontier in Python .

Link to wikipedia : https://en.wikipedia.org/wiki/Modern_portfolio_theory


Markowitz's Portfolio theory has been published in the early '50s but it still one of the most valid intuitions in the portfolio optimization research.

Markowitz's theory is based on two fundamentals hypothesis:

    The investors are risk-averse.

    The investors want to maximize their returns.


Given these constraints, every security can be mapped in a two-dimensional space.

The first dimension is Expected Return, the second one is Volatility.

The Expected Return is the average of the returns and Volatility can be defined as the deviation from this Expected Return.

In a more statistical perspective Volatility is the Standard Deviation of the returns based on historical values.


To better understand Markowitz's work i want to refresh the following concepts:

    Risk : It is a measure of uncertainty and is defined as an adverse outcome.
    
The risk is composed of two subtypes of risks.

    Systematic risk :
    Systematic risk is the inevitable risk, the non-diversifiable risk present in every investment.
    
    Market risk:
    The Market risk is the result of the relationship between the securities in terms of returns and volatility.



A quick example:

If the market of cars falls, a diversified portfolio composed of different sectors stocks ,won't suffer as a single sector one. In the well-diversified portfolio not all the stocks are connected, so the loss will be reduced.

In the most common optimization, the time frame analysis is yearly based.

      In the following Notebook i will demonstrate Markowitz's theory step by step .

      I'll be using Python to perform calculations and Quandl for data acquisition.

      Quanld : https://www.quandl.com/
