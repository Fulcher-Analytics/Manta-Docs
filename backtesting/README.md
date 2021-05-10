# Backtesting

You can back test a strategy by either pressing backtest on the home page, or going to the back test menu on the side bar.

![Backtesting Page](https://github.com/Manta-AI/Manta-Docs/raw/master/src/imgs/backtest-1.png)

You can now fill in the following values:

* Principal: the initial starting capital that your bot will trade with 
  * You may get an error, such as "Your bot did not make any trades". Most of the time this is caused by your bot not having enough capital to 

    enter a position. To fix this, simply increase the value.
* Period: the historical time interval your bot will trade on 
  * Note: Due to data limitations, if you are using a bot that trades on a one minute interval, you will only be able to test back for five days. 
* Slippage Enabled: This will invoke [slippage](https://www.investopedia.com/terms/s/slippage.asp). This will ensure your strategy is more realistic to 

  how the actual markets behave. We recommend leaving slippage enabled to get the most acurate results. 

* Commission: The dollar amount that will be subtracted from your balance whenever a buy or sell order is placed. 

After filling in these values, you are now ready to run your backtest. Press Test and you will soon be connected to our servers and results will be returned shortly. It's important to note the values will show NaN as the test is running, this is perfectly fine as the proper values are being awaited.

![Settings](https://github.com/Manta-AI/Manta-Docs/raw/master/src/imgs/backtest-2.png)

When the test is complete, you will be greeted with a screen that looks similiar to the follwing:

![Results Page](https://github.com/Manta-AI/Manta-Docs/raw/master/src/imgs/backtest-3.png)

Note the strategy featured here is a basic Moving Average Crossover strategy that uses very basic technical analysis; thus, it will not make any money. Slippage is also enabled.

Near the top, basic statistics about your test are given. Optimizing these values is the key to a good strategy. Below, you'll see a trade log every trade your bot made. Note the spots were the graph seems to have no change, this is the time when the market is closed overnight \(this will appear only on minute frequencies\)

![Trades Page](https://github.com/Manta-AI/Manta-Docs/raw/master/src/imgs/backtest-4.png)

To rapidly test, you can press New Test at the bottom of the page, then Quick Edit to make minor changes to your bot and change parameters in your test.

