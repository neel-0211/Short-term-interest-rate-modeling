# Short-term-interest-rate-modeling

Fitted Vasicek Model by solving for a non-linear optimization equation (Root Mean Square Error) in Python (using SciPy) and simulated one million random paths to price different interest rate options such as Forward Rate Agreement (FRA), Swap, Accrual Note, Floating Rate Note, and Swaptions.

Constructed Black-Derman-Toy binomial lattice to calibrate the model parameters to fit the term structure of interest rates (yield curve) and the volatility structure semi-annually up to 15 years.
