---
layout: post
image: /images/pasta.jpg
page.image: /images/pasta.jpg
summary: Food and drinks, online shopping, and maybe pasta machines.
excerpt: Food and drinks, online shopping, and maybe pasta machines.
time: 3 minute read
title: As GDP hits an unprecedented low, where do we spend our money these days?
---
The [U.S. Gross Domestic Product (GDP)](https://en.wikipedia.org/wiki/Gross_domestic_product) dropped by 33% in the second quarter of 2020. The drop was the most drastic ever. **Seriously.** [Ever](https://www.npr.org/sections/coronavirus-live-updates/2020/07/30/896714437/3-months-of-hell-u-s-economys-worst-quarter-ever).

How much we spend on goods and services is a huge factor in calculating GDP. It might be obvious that Americans are spending less money on restaurants and bars. But are we spending that money somewhere else?

I got a little curious about this while I was unboxing my brand-new pasta machine a few nights ago. Yep, I splurged on a gadget that has taken my culinary game to the big league. And by looking at the data, you probably have too.

<br>

<p align="center">
  <img src="{{ site.baseurl }}/images/pasta.jpg" />
</p>
<div align="center"><em>Pasta machine cutting some fettuccini. Or maybe its lasagnette? Tagliatelle? There are so many names for pasta!</em></div>

<br>
<br>

***

## How do you measure spending in the U.S. economy?

I grabbed data from the U.S. Census Bureau's Monthly Retail Trade database. This database includes monthly retail sales, broken down by retail sector.

I calculated differences in projected vs. actual spending in each retail sector since March, 2020. Projected spending was estimated using linear models of spending from November 2019 through February 2020. The measurements are the cumulative difference in projected vs. annual spending from March through June in each retail sector. 

<br>
<br>

***

## Where are we spending our money?

My hunch that I might not be the only person upping my culinary game was right. **Food and beverage store sales have increased by about 8,800% since the end of February. That is an increase in sales of about 7.5 billion dollars.**

That also might explain the slew of home-streaming cooks - like the amazing baking videos from [Christina Tosi on Instagram](https://www.instagram.com/christinatosi/?hl=en). 

<br>

<iframe src="https://public.tableau.com/views/Percentchangeinretailsales/Sheet2?:showVizHome=no&:embed=true" width="100%" height="500"></iframe>
<div align="center"><em>Percent difference in projected vs annual spending in retail sectors since February 2020. Hover, click, or tap on bars to see differences in dollars spent. </em></div>

<br>

In addition to food and drinks, we are also spending more online, on cars, hobbies and books, and building materials and garden supplies.

But where have we spent less? **Clothing and accessories. This sector decreased by more than 6,000%, dropping about 5 billion dollars in sales since the end of February.** Second to clothing, electronics and appliance store sales declined by 4,800%, or 1 billion dollars.

Aside from these two giant dips in spending, we spent less in restaurants and bars, department stores, health stores, gas stations, and on furniture. 

<br>
<br>

***

## How massive are the changes in spending?

I thought about how to convey the magnitude of changes in spending. A 6,000%, 5 billion dollar decline in clothing spending - how big is that? I am not sure the numbers really convey what is going on here.

Just looking at the data might be the best way to see how unprecedented these spending changes are. So I have made an interactive graph to explore retail sales data since 1992. Click through some of the sectors and change the years to get a feel for how unprecedented the changes in spending are.

<br>

<iframe src="https://waltscience.shinyapps.io/shinymrt/" width="100%" height="1150px"></iframe>

<br>
<br>

***

## What does the future hold for the GDP?

Unfortunately, retail data isn't very useful for forecasting future GDP in a pandemic. But we don't need forecasting to know the outlook isn't great.

Some economists have argued [enhanced unemployment benefits and social safety net programs kept the GDP from falling even further in the second quarter](https://www.cnbc.com/2020/07/10/unemployment-boosts-will-help-recovery-more-than-new-stimulus-checks.html). Many of those benefits expired on July 31st. 

Others argue [new funding should focus on states and municipalities](https://www.forbes.com/sites/lizfarmer/2020/07/30/bailout-stimulus-federal-relief-recovery/#6fbc9e895678), which are face massive revenue shortfalls. Yet, there seems to be little desire to grant federal stimulus money to states.

In any case, [an unprecedented, unheard-of, unimaginable portion of our economy is being kept afloat right now by a firehose of U.S. aid aimed at corporations and citizens](https://www.barrons.com/articles/for-the-first-time-ever-uncle-sams-aid-to-u-s-tops-quarterly-gdp-51596244795). As the government begins to close the tap, *the economy will start to sink*.

Until then, I will be perfecting homemade pasta - when it's done coking, it floats.

<br>
<br>

***

**More opinion on the GDP**
* [Did a third of the economy really vanish in just three months?](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=newssearch&cd=&ved=0ahUKEwj6zp2R0oDrAhXSKM0KHeJ4BuQ4ChDF9AEINDAB&url=https%3A%2F%2Fwww.washingtonpost.com%2Fbusiness%2F2020%2F07%2F30%2Fdid-third-economy-really-vanish-just-three-months%2F&usg=AOvVaw2Ox_VV98LJQnNtomgiq_0Q)
* [Ignore GDP Plunging 33%. Pay Attention To The 9.5% Decline](https://www.forbes.com/sites/chuckjones/2020/07/31/ignore-gdp-plunging-33-pay-attention-to-the-95-decline/#635c4c9f2640)

<br>
<br>

***

*Retail sales data source: U.S. Census Bureau Monthly Retail Trade database, 1992-2020.*

*Data and R code available on [GitHub](https://github.com/waltscience/retailspending)*
<br>

{% include twitter_card.html %}