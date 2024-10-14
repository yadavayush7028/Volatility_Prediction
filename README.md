
# Volatility Prediction on Wheat Futures Prices

This repository is a personal group project created by my friend Ayush and me, where we predict the volatility of wheat futures prices over the years in both the US and Indian markets.




## Progress
- No signigicant autocorrelation detected in returns of daily, weekly and monthly returns% of US wheat prices or Indian wheat prices.
- Extracted the temperature and precipitation details for top 3 wheat producing states of US (North Dakota, Kansas, Montana) and India(Uttar Pradesh, Madhya Pradesh, Punjab), respectively.
- Applied Garch(1,1) model on the returns%
- Applied complex garch models with higher p and q after checking for autocorrelation and partial autocorrelation on squared residuals of ARIMA model on the returns %
- No significant decrease in AIC and BIC

## Authors

- [Ayush Yadav](https://github.com/yadavayush7028)
- [Bibek Paul](https://github.com/X-Warrior361)

