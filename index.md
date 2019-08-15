---
driveId: 1w68Ee5j0dYrICXOFYAnG4MicH3gNwGTg/preview
driveId2: 1-bfZ5j-9M-ZIdk5q6McbZMZ38oM0EHoJ/preview
---

# Volatility Surface Explorer [(Webapp Link)](http://vol-app-prod.herokuapp.com/)

![Image](/assets/Volatility_Surface.png)
![Image](/assets/Volatility_Simulator.jpg)

The volatility surface explorer is a reactive [webapp](http://vol-app-prod.herokuapp.com/) I created for **exploratory data analysis of implied volatility surfaces**. You can view historical surface dynamics in high resolution (up to 10 second intervals) through graph animations and reactive surfaces.

Load up a preset within the app to explore interesting surface dynamics during times of low liquidity in options such as large moves in spot price and in expiring options. 

Created in Plotly Dash (Python), CSS and HTML.

# Volatility Surface Simulator (Internal Tool)
The volatility surface simulator is an interval backtesting tool I created to **backtest and benchmark my own improvements to the production stochastic volatilty model.**

## My Improvements:
- New weight functions
- New penalty functions
- No-arbitrage constraints
- Robust regression methods
- L1 norm methodologies to handle outliers more effectively
- New liquidity model
- Smoothing functions
- Constrained optimization methods

## Video Examples

### Surface Shock Recovery
{% include googleDrivePlayer.html id=page.driveId %}

### Option Nearing Expiry
{% include googleDrivePlayer.html id=page.driveId2 %}
