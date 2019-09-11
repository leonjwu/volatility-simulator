---
driveId: 1w68Ee5j0dYrICXOFYAnG4MicH3gNwGTg/preview
driveId2: 1-bfZ5j-9M-ZIdk5q6McbZMZ38oM0EHoJ/preview
---
# [LINK](http://app-prod-dev.eu-west-2.elasticbeanstalk.com/)
# Volatility Surface Explorer [(Webapp Link)](http://app-prod-dev.eu-west-2.elasticbeanstalk.com/)

![Image](/assets/2D.png)
![Image](/assets/3D.png)

This volatility surface explorer is an options trading and pricing tool I built, enabling market makers and traders to visualise real-time and historical simulations of volatility surfaces, market quotes, and trades.

Using the tool, you can **view proprietary implied volatility surface marks generated from my own model**, and explore live or historical volatility surfaces in 2D or 3D through simulations.

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

These examples show how my model improved the stability and accuracy of the volatility smile during times of extremely low liquidity.

### Surface Shock Recovery
{% include googleDrivePlayer.html id=page.driveId %}

### Option Nearing Expiry
{% include googleDrivePlayer.html id=page.driveId2 %}
