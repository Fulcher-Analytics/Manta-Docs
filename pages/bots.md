# Bot Building

## Introduction

Manta Trader's essential purpose is to allow you to build and create "bots" to trade the markets.
This guide will introduce you to the different types of bots, how to build them, and the interworkings
behind them.

"bot" - a program that buys and sells securities based on certain conditions

To build a bot, go to the Manta Trader Dashboard, and press new Bot. Select Custom Built or Prebuilt,
and follow the instructions below.

#### Bot Types

1. **IFTTT** - IFTTT stands for "If This, Then That". It's a way of building bots that revolves
   around conditional logic. IFTTT bots give you fine control and make bot building easy for beginners.

2. **Indicator Based** - Indicator based bots are bots that buy and sell based on Technical Analysis
   Indicators. Manta offers over 200 technical analysis indicators, including some added ones such as
   Support and Resistance and Sentiment Analysis. Indicator based bots allow you to add infinite amount
   of indicators, and then assign them certain weights. That way, you can fine tune how much each indicator
   contributes to the bots decision.

3. **Fixed Interval** - Fixed interval bots are "dumb". They do not have any conditional logic, they simply
   buy (or sell) on a fixed interval, disregarding the market conditions. Fixed Interval bots allow you to perform
   strategies such as Dollar Cost Averaging. An example of a Fixed Interval Bot would be one that buys 1 share of the
   S&P 500 index every month.

4. **Prebuilt Bots** - Prebuilt bots are custom built bots that are designed by the Manta Trader Team. Prebuilt bots
   typically involve more advanced strategies that can involve things like Artificial Intellegence and advanced statistical
   models.

---

## IFTTT Bots

IFTTT is a beginner friendly way to build bots that follow a sequential execution pattern. There are 2 main things to get familiar with: 

* **IF** statements (Triggers) - When to do
* **THEN** statements (Actions) - What to do 

Let's say for example you want to buy TSLA stock after the stock was gapping down and also had a higher than average volume, in other words, you expect the price to rise up again given the higher than usual activity. In that case all you need to do is add 2 **IF**s and 1 **THEN** as such:

![Simple IFTTT Example](https://raw.githubusercontent.com/Manta-AI/Manta-Docs/master/src/imgs/Manta-IFTTT-simple.png "Simple IFTTT Example")

Simple, right? But what if you want to buy TSLA if **either** of the IF conditions is satisfied? This is why we have added **IF Mode**, which allows you to pick how you want your Triggers to be treated:

* **AND** - All conditions must be satisfied to procede to next Actions
* **OR** - One of the conditions must be satisfied to procede to next Actions
* **MOST** - The majority (strictly more than half) must be satisfied to proceed to next Actions

![IF Mode Example](https://github.com/Manta-AI/Manta-Docs/blob/master/src/imgs/Manta-IFTTT-ifmode.png "IF Mode Demo")

That is all you need! Lastly, let's imporve on our TSLA example. So now we have figured out when to enter the market, so when should we exit? How about we exit when after the stock has been gapping up and the volume is lower than average?

![More Advanced Example](https://github.com/Manta-AI/Manta-Docs/blob/master/src/imgs/Manta-IFTTT-simple2.png "More Advanced Demo")

Done! Now go make some IFTTT bots and feel free to mix things up!




