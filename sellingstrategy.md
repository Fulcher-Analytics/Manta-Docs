# Selling Your Algotrading Strategy

## Introduction

Manta Trader allows you to sell one of your strategies to our users in exchange for a monthly subscription. If your strategy is profitable, you can go to our \[Algo Trading Pro\]\('[https://mantatrader.com/algotradingpro](https://mantatrader.com/algotradingpro)\) page and apply to see if your strategy meets the criteria.

## Strategy Criteria

Your strategy will have to have a few key things in order to qualify. Namely:

* Strategy Information
  * You should include your strategies name, description, and other necissary info
  * You should state what market your algo works in. Is it best for cryptocurrency, stocks, large cap, small cap?
* Backtesting Results
  * You must supply us with all of the 9 major intervals for backtesting such as 1 month, 5 day, etc. To see all of the required intervals, see the \[Algo Trading Pro\]\('[https://mantatrader.com/algotradingpro](https://mantatrader.com/algotradingpro)'\) page.
  * You don't _have_ to be profitable for every interval, we like to see at least 5 of the 9 be profitable, but if your strategy is exclusively for ultra long or short term we will still consider it.
  * Your strategy should be submitted with all of the 9 backtesting intervals.
* Sharpe, CAGR, and other metrics
  * Sharpe and CAGR must be given for each of the backtesting intervals
  * Return on each interval should be clearly stated
  * Risk/Reward per trade should be stated
* Clean python codebase
  * Your strategy should take a df full of pricing data, and return a value of the range \[-1, 0, 1\]. -1 being short, 0 being hold, 1 being sell.
  * Your code should be easily readable, and our engineers should be able to modify it

    and perform unit and security tests while integrating it into our codebase.

## Payment Details

Our business model has three different plans, see our \[pricing page\]\('[https://mantatrader.com/pricing](https://mantatrader.com/pricing)'\) for details. You have two options for payment of your strategy:

* Get percentage of users monthly subscription fee
  * For an exact estimate, please contact our team.
* Charge an additional fee for using your strategy.
  * We allow you to offer a seperate fee that goes to you for offering your strategy, however, it will come at the expense of not as many users using your algo.

