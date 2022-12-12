# Crypto-currency-Exponential-moving-average
Here is a portfolio construction for 30 crypto currencies. We are using the exponential moving average of 20 days and 50 days as our signal generator. 
The initial strategy is basically to compare 20-day line and 50-day line. If the 20-day line is above the 50-day line, it means that for this specific
crypto, the short term potential is higher than the long term performance of the crypto, which means we need to long the crypto currency.

1. conducted original strategy ---- long the crypto if the signal is positive, money evenly distribute on 30 crypto (matrix multiplicity: signal times daily return)
2. refinement 1: Risk-Weight Portfolio. using the position to divid 20 days rolling volitality, to adjust the weight of each
3. refinement 2: instead of using equal weighted for 30 crypto, we use 20-day exponential moving average directly minus 50-day ema to generate the signal,
   and only choose one to long and one to short. 
