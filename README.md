# Probability of Default calculation in R
The purpose of the project is to calculate one-year probability of default. 
Currently, the project only includes probabilities based on the KMV-Merton model.
Here is the link to my repository, in which one can find probability of default estimation in Python, using Machine Learning models: https://github.com/PawelChruszczewski/Corporate-Defaults---ML-Models

In the selected variant of the Merton model, I considered only two types of liabilities, one class of debt and one class of equity. 
I assumed that the company's capital structure consists solely of debt and equity. 
I also assumed that the market value of the company's underlying assets was subject to a geometric Brownian motion. 
In addition, I assumed that the debt would be a single zero-coupon bond consisting entirely of short-term debt and half of the long-term debt.
As a risk-free rate, I used the daily observations of the annual rate of Treasury notes obtained from the Federal Reserve statistics.

In the project, I used bankruptcy data from the UCLA LoPucki database and fundamental data about companies from the Compustat database.
The data cleaning process was conducted in Python. 
If one would like to get more details on this process, please contact me via LinkedIn: https://www.linkedin.com/in/pawe%C5%82-chruszczewski-460689151/
