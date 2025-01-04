# kalman-pairs-trading

## What is Pairs Trading?

Pairs trading is a market-neutral strategy that capitalizes on the mean-reverting behavior of two correlated assets. When the relationship between two stocks diverges, traders can take a long position on the underperforming stock and a short position on the overperforming one with the idea that the stock prices will eventually re-align.

In Pairs Trading, we use two securities that we suspect may be co-integrated rather than running statistical tests over all pairs to avoid comparision bias.

**Multiple comparisons bias** is simply the fact that there is an increased chance to incorrectly generate a significant p-value when many tests are run, because we are running a lot of tests. If 100 tests are run on random data, we should expect to see 5 p-values below 0.05. If you are comparing n securities for co-integration, you will perform n(n-1)/2 comparisons, and you should expect to see many incorrectly significant p-values, which will increase as you increase.

