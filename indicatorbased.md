# Indicator Bots

Indicator bots are an alternative way to define trade entries and exits. Although they are a little more complex, they can prove to be a powerful tool for trading all types of markets. There are two steps to creating an indicator based bot:

* **Settings** - In the settings panel you will define the bot's name, trade frequency, etc. Remember if you don't know what something is, you can hover over the fields label and it will display a brief message regarding it's purpose.
* **Strategy** - In the strategy panel, you define the indicators to use. Read on to learn how to setup a combonation of indicators.

## Defining a Strategy

The first thing you will want to do is select an indicator to use, for example, let's choose the SMA:

\[insertimage\]

After you select an indicator, the required paramaters will appear. For SMA, you have to enter the rolling period:

\[insertimage\]

Next, you must enter the weight. The weight determines how much "Decision power" the specific indicator will have in the final bot. For example, say you have two indicators, a SMA and EMA. The SMA has a weight of 1 and the EMA has a weight of 2. That would indicate the SMA has 33% of the decision power, and the EMA has 66% of the decision power. Now, if the SMA indicator returned a buy signal, but the EMA returned no signal \(hold\), then the algorithm would hold.

As you add more indicators and different weights, you can create a very complex algorithm. See below for a complex algo:

\[insert image\]

Note: the weight values can be anything you'd like, they are normalized later. For example you can use a 0-10 scale, or a 0-100 scale, etc.

