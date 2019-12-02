---
layout:     post
title:      "simple valuation: one ring to rule them all!"
description: "how i think about valuing stocks"
date:       2018-12-25 17:00:00
author:     "cj"
header-img: assets/img/posts/header-img/woman-typing-macbook.jpg

categories:
  - Tips/Thoughts
---

# why paying for votes is rational

 **** This note is for retail investors only . This is only for educational purposes and does not constitute investing advice 🙂 **** 

Some folks say valuation is a science, others say it’s an art… I say it is simple math. In a few steps I will show you how you can use 8th grade maths and publicly available information to assess any company for profitable investing.

It all rests on the obvious question. What is the value of a company? Two answers. One, it is the sum of its expected future cash flows discounted at some rate (usually it’s cost of capital). Two, the value of a company is what anybody would pay for it in the market.

Both answers are correct theoretically. Also both answers will give you the same result if we assume that markets are fully efficient. That is, if there is ever a difference between the **real value** (discounted cash flows) and the **market value** (willing buyer, willing seller) a smart investor will arbitrage that difference away.

![img](https://conyekwelu.files.wordpress.com/2018/12/a3aed-1jPEEQ0mtS32PLKyCmuOjeg.png?w=1088)

rv is a modified form of the Gordon Growth Model

We will make only **one main assumption** that epsilon (our error term below) is really small. That is, the market may not be fully efficient and there may be differences, but frictions (like trading commissions) prevent most folks from taking advantage of them.

![img](https://conyekwelu.files.wordpress.com/2018/12/37198-1TbDlHq-b1AwBduNkF3cFqQ.png?w=1088)

The One Equation!



### Case Study: Netflix

So what do we know about Netflix? Video streaming company, about 140 million subscribers… bla bla bla. All unimportant, at least for now. Just show me the numbers!



**Step One: What is the Market Value?**

Get on that beautiful public service called [Yahoo Finance](https://finance.yahoo.com/quote/NFLX?p=NFLX)! From there we see that the Market Cap (i.e. **market value** of the entire company) is **$114.31B**

![img](https://conyekwelu.files.wordpress.com/2018/12/38e1a-13EVsF8wjszNsuCpxdDvi-A.png?w=1088)

*Source: Yahoo Finance*



**Step Two: How much should Investors get paid for holding Netflix?**

You can determine this two ways. You can answer the question yourself by using your personal expected rate of return (based on your opportunity cost).

Or, find out how much lenders are charging them now (google search or read 10K/Q). Oh [look](https://markets.businessinsider.com/news/stocks/netflix-stock-price-issues-2-billion-junk-bonds-to-fund-content-spending-2018-10-1027640423)! Smarter people with less risk (lenders) expect 6.38%, so I’m going to add some [premium](https://www.investopedia.com/terms/e/equityriskpremium.asp) of 6.62% and end up with **13%** (just to make our calculations easier).

![img](https://conyekwelu.files.wordpress.com/2018/12/0408d-1SKKcTl_xskesBbG5Bm2KYw.png?w=1088)

*Source: MarketsInsider*



**Step Three: What is the Real Value?**

Trick question! we have already agreed that the **real value** is the same as the **market value**. Using simple algebra and solving for our expected annual cash flow:

![img](https://conyekwelu.files.wordpress.com/2018/12/279ac-1AVKsoQBKohmgzky_69eE1g.png?w=1088)

We gain some useful information — Netflix should be bringing in approximately **$14.86B** in free cash flow every year for a **real value** of $114.31B.

**Step Four: Compare the most recent actual Annual Cash flow with our expectations from Step Three above.**

So we go back to [Yahoo Finance](https://finance.yahoo.com/quote/NFLX/financials?p=NFLX)! to see what the actual cash flow was in 2017. Uh uh, it was **-$1.79B.** Not good.

![img](https://conyekwelu.files.wordpress.com/2018/12/8b94a-1DUPdsMHO4pg8jUar2Q4oaw.png?w=1088)

So I might try a different proxy for the company’s operating cash flows like maybe the Operating Income (OI). Much better at **$0.84B**.

*Note: you can even decide to use the Gross Profit as a proxy to bias your results. Just keep the direction in mind.*

![img](https://conyekwelu.files.wordpress.com/2018/12/dbc1f-1KM5lFxF1cpe1seTQLtPCRg.png?w=1088)

*Source: Yahoo Finance!*

Now we compare these numbers with our expectations… Oops! Looks like we should be making ***about18 times\*** the current **OI** at this valuation!

![img](https://conyekwelu.files.wordpress.com/2018/12/02158-1QwC69GEkI0pqufgmL_UobA.png?w=1088)

**Step Five: Can we explain the difference?**

What must be true for the value to “make sense”? This is where specific information about the company matters.

Let’s consider **growth**. It could be that the current circa 140m subscribers (less than 50% in US) is a drop in the bucket afterall. There’s 7 billion people on earth and no major (lol) competitor. Or maybe they could increase prices?

![img](https://conyekwelu.files.wordpress.com/2018/12/4fb6e-1RGi8Sc9Q3GS9JgmsM_YlTA.png?w=1088)

Not likely! By solving for the net growth rate (basic algebra again) we see they would have to grow 12% every year in perpetuity.

You can keep ruling out alternative explanations like this by making simple tweaks to your model. For example, I have a version offline that accounts for scenarios like a change in their churn rate, customer acquisition costs, content spend etc. Finance types call this “sensitivity analysis” or “scenario analysis”. Summary, in this particular case it doesn’t look good.

*Segue on Market Cycles:*

*Part of the reason for the deviation of the market value of from the real value might be macroeconomic factors like a loose monetary policy. If there’s too much money out there chasing too few assets then prices could be bid up far above their intrinsic value. Markets go through cyclical booms and busts. Some investors try to* [*time the market cycles*](https://www.amazon.com/dp/B078977BRM/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)*, others* [*anticipate and profit off them*](https://www.amazon.com/dp/B00D7P2K1W/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)*.*



**Step Six: Select an Entry Point (aka Decide)**

So what to do next? Only three decisions can be made — Buy, Sell or Do Nothing (Hold).

Buy if the company is making more money that you expect (and you are convinced of their future prospects — i.e. there is no hidden reason or risk behind the apparent cheapness). If you practice the [voodoo arts ](https://www.investopedia.com/terms/t/technicalanalysis.asp)of Technical Analysis, you can time your entry with the right chart setup.

Sell if the company is making way less money than you expect (and you have ruled out plausible explanations as in Step Five). More practically, you can do this using [Put Options](https://en.wikipedia.org/wiki/Put_option).

Do Nothing, if you are not convinced on a trade direction by your analysis.



**Final Words**

A final concept to mention would be the Margin of Safety. Just like an engineer constructing a bridge, you want to leave some wiggle room for unexpected events. You can apply this in your analysis by using a much higher required rate of return (e.g 30%).

While this model appears “simple” it covers most of corporate finance and stuff that more complex models would. As one of my professors would say, you don’t have to be precise, you just have to be directionally right with a large enough margin of safety.

Happy Hunting!