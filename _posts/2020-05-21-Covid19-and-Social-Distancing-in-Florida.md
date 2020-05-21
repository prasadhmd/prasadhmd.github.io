---
layout: post
title: "Covid-19 and Social Distancing in Florida"
date: 2020-05-21
---

Coronavirus is affecting daily lives of people almost everywhere in the
world. The social impact as well as economic burden on personal and
state level is immense as countries and communities adopt some form of
social distancing and isolation of people. With lot of discussion and
debates on the effectiveness of state lockdown orders and attempts to
prevent people from gathering, I decided to make a simple comparison
of numbers. The data is publicly available from [European Centre for
Dicease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide)
and [New York Times](https://github.com/nytimes/covid-19-data).  

Please note that this is a simple excercise to compare total number of
coronavirus cases found in Italy and the state of Florida, USA. The
population is Italy is about 2.8 times of Florida and therefore the
number of infections were devided by the population ratio. Also, the
cumilative curve of Florida was shifted forward by 44 days as the
covid19 infections started much earlier in Italy. The curves
surprisingly overlap until April 4th. Florida governer issed [stay at
home order](https://www.usnews.com/news/best-states/florida/articles/2020-04-01/florida-governor-issues-statewide-stay-at-home-order)
on April 1st effectiveon April 3rd and I am not sure this
is the single reason responsible for this improvement. I compared the
other states such as New York and did not find such an overlap.

![covid19 cumilative cases](/assets/covid19.png)

The total percentage of population infected from each state was
obtained and compared in a similar way. Several groupings of states
were found and most of these groups do not share any obvious
geographical or other resemblence. For example, California, Kentucky,
Arizona, Utah, Texas, Wisconsin, and North Carolina share similar
covid-19 spread over time among the population of individual
states. In addition, Florida and Nevada share such similarity as well
as states Oklahoma and Wyoming, and Hawaii and Montana shows similar
behaviours as shown in the following graphs. Note that these curves
are shifted along the time axis so that they are overlapped. We did
find some other states such as New York and New Jersey to be somewhat
similar although these curves did not match very well. We used a
simple algorithm implemented in Python to calculate the smallest
possible deviation from each other and above groups were selected in
such a way that the average shifts in each group is mathematically
consistant.

![covid19 cumilative cases](/assets/CA_alike.png)
![covid19 cumilative cases](/assets/FL_like.png)
![covid19 cumilative cases](/assets/OK_alike.png)
![covid19 cumilative cases](/assets/TN_alike.png)
