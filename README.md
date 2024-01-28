# **Calculation Of Option Greeks and Implied Volatility in Python**

The aim of this notebook is to calculate Option Greeks and Implied Volatility using Python. The function takes input in a similar form to the popular Hoadley add-in used in Excel.


## **Overview:**

### **Purpose:** 
Implements Black-Scholes option pricing model and implied volatility calculation.
### **Functions:**
```blackScholes(calculation_type, Option_type, K, S, T, sigma, r)```: Calculates option price, delta, gamma, vega, theta, or rho.
```implied_volatility(Option_type, K, S, T, Option_price, r, tol, max_iterations)```: Estimates implied volatility using iterative search.
Key Features:

Calculations: Performs price, delta, gamma, vega, theta, and rho calculations for both call and put options.
Implied Volatility: Estimates implied volatility using numerical methods.
Input Validation: Includes checks for invalid inputs (e.g., NaN values, zero strike price).
Error Handling: Handles potential errors (e.g., incorrect option type).
Examples: Demonstrates usage with sample calculations for call price and implied volatility.
Structure:

Imports: Imports necessary libraries (numpy, scipy.stats, math, warnings).
Function Definitions: Defines the blackScholes and implied_volatility functions.
Example Usage: Demonstrates example calculations.
Function Definitions (Repeated): The function definitions are repeated at the end, likely due to a formatting error.
Additional Information:

Variables:
calculation_type: Specifies the type of calculation to perform (price, delta, gamma, vega, theta, rho).
Option_type: Specifies the option type (call or put).
K: Strike price.
S: Underlying asset price.
T: Time to expiration (in years).
sigma: Volatility.
r: Risk-free interest rate.
Option_price: Market price of the option (used for implied volatility calculation).
tol: Tolerance level for implied volatility calculation.
max_iterations: Maximum number of iterations for implied volatility calculation.
