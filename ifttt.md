# IFTTT Bots

IFTTT is a beginner friendly way to build bots that follow a sequential execution pattern. There are 2 main things to get familiar with:

* **IF** statements \(Triggers\) - When to do
  * You can have an **OR IF** or an **AND IF** to take into account previous conditions 
  * Using a Technical Indicator is a type of **IF** statement
* **THEN** statements \(Actions\) - What to do 

Let's say for example you want to buy TSLA stock after the stock was gapping down and also had a higher than average volume, in other words, you expect the price to rise up again given the higher than usual activity. In that case all you need to do is add 2 **IF**s and 1 **THEN** as such:

![Simple IFTTT Example](https://raw.githubusercontent.com/Manta-AI/Manta-Docs/master/src/imgs/Manta-IFTTT-simple.png)

Simple, right? But what if you want to buy TSLA if **either** of the IF conditions is satisfied? This is why we have added **IF Mode**, which allows you to pick how you want your Triggers to be treated:

* **AND** - All conditions must be satisfied to procede to next Actions
* **OR** - One of the conditions must be satisfied to procede to next Actions
* **MOST** - The majority \(strictly more than half\) must be satisfied to proceed to next Actions

![IF Mode Demo](https://github.com/Manta-AI/Manta-Docs/blob/master/src/imgs/Manta-IFTTT-ifmode.png) That is all you need! Lastly, let's imporve on our TSLA example. So now we have figured out when to enter the market, so when should we exit? How about we exit when after the stock has been gapping up and the volume is lower than average?

![More Advanced Demo](https://github.com/Manta-AI/Manta-Docs/blob/master/src/imgs/Manta-IFTTT-simple2.png)

Done! Now go make some IFTTT bots and feel free to mix things up!

