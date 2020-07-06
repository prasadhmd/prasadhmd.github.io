---
layout: post
title: "Spread of covid-19 in the US"
date: 2020-07-05
---

Coronavirus situation in the United States have worsened after my last
update in late May and that analysis seems no longer valid. The states
cannot be grouped as I did before. Therefore, I explored the data more
to see if there is any more insight we can get. Again, I am using the
publicly available data from [European Centre for Decease Prevention
and
Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide) 
and [New York Times](https://github.com/nytimes/covid-19-data).

Most of the news reports and some analysts use reported case count as
a measure to compare the situation in different states. However, this
is not totally accurate in my opinion. A highly populated state can
have more cases than a state that has a lot less population yet the
proportionately less infected. For example, Florida reported close to
100 000 more total number of infections as of today than the state of
Arizona. However, Florida has nearly three times the population and
therefore Arizona has much higher percentage of infected
population. This is evident from the reports that they are running out
of ICU beds and Florida is not experiencing this type of
situation. Therefore, I am using the percentage of total (cumulative)
infections as the measure to compare different states.

When I look at the data, I see some sates have flattened curves
meaning there are little to none new cases while some states are
experiencing a surge. I developed a metric to categorize states
depending on this behavior. I used the relative change of the number
of cases (change of numbers in two consecutive days divided by the
total case count) during last five days. This quantity is called the
daily new infections rate and is less than 0.05% for the states with
flattened curves and as high as 5% at the places where cases are
surging. For clarity, I divided states in to six categories >5%,
4-5%, 3-4%, 2-3%, 1-2%, 1-0.5%, and 0.5%>. The first category contains the
states with worst outbreak while the last with flattened curve with
least new cases.

The results are shown in the following plots. States New York, New
Jersey, Massachusetts, Connecticut, and District of Columbia have the
least new infection rates while Arizona, Florida, Idaho, and Montana
with nations worst new infection rates during last five days. State of
Arizona has the highest infection rate and Florida comes in next. As
you can see, all four states show a sharp exponential rise in number
of cases recently. Arizona ended its stay home order on May 16th and
Florida ended its stay home order on May 04 while Florida keys opened
up on June 1st. State of Idaho opened bars on May 30 by moving to
stage 3. Montana eased its restrictions on June 1st by increasing
the number of people allowed in restaurants, bars, pools and gyms to
75% capacity. It is interesting to observe a sharp increase in cases after
about two weeks of opening each sate although further analysis is
necessary to verify whether this is true.

On June 15th, New Jersey opened up outdoor dining at all times of day or
night,in-person retail and child care services with restrictions. New
York city where the heaviest outbreak of the world occurred began phase
2 on June 6th with lot of restrictions. The state of Massachusetts
opened indoor dining at restaurants as well as nail salons and fitting
rooms on June 22nd while The District of Columbia entered phase 2 of
reopening on the same day by opening restaurants and stores to 50%
capacity as well as gyms, and salons. Connecticut opened indoor facilities
including gyms, and hotels on June 20. Note from the graphs that all
of these openings were occurred after significantly reducing the
infections rates. This is significant for New York and New Jersey as
they have the highest percentage of infections in the country (around
2%). 

Other states are in different categories as shown in the following
plots. Notice that South Carolina, Nevada, and Texas have the sharpest
rise of infection rates beside the category 1 states. Alaska is one of
the first states to completely reopen by May 22 and started surging
within a week or so despite the fact that they flattened the curve
significantly by then. The state of Nevada sees a sharp increase in
infected population after resuming the operation of casinos and gaming
on June 4th. Oklahoma is another example of a sharp increase of
infections two weeks after completely opening on June 01.

On the other hand, states Pennsylvania, Illinois, Michigan, Maryland,
Colorado, Nebraska, New Hampshire, and Rhode Island have the lowest
new infection rates other than category 7. These states have almost
flattened the curve. Note that about 1.6% of the total population of
Rhode Island is infected. This may be a result of being a small state
closer to NY, CT, and MT which recorded large amount of infections.

Another factor in controlling the outbreak is wearing masks, as most
health officials including WHO now agrees. Connecticut made a
statewide mask mandate on April 20 while New York and New Jersey
required wearing masks on April 17 and April 08, respectively. DC
mayor ordered the same on May 16. Massachusetts Governor issued an
order requiring the use of face coverings or masks on May 06. As we
can see from the cumulative percentage of infections plot, all the
states that mandated masks early on have seemed to control the spread
of the virus. California, on the other hand, did not mandate masks
until June 18 which still experience a large infection rate. States
Illinois and Rhode Island imposed mask mandates on May 01, and May 08
where they two see an improvement after few weeks.

I have to emphasize that these are mere observations from the graphs
and further analysis is required to come to a conclusion
definitively. However, more than a few states show that the infection
rates are higher unless there is a mask mandate together with not
reopening until the curve is significantly flat. I will gather more
data to make a further analysis in a future post.

![covid19 cumulative cases](/assets/covid19_<0.005.png)
![covid19 cumulative cases](/assets/covid19_>0.05.png)
![covid19 cumulative cases](/assets/covid19_0.01>0.005.png)
![covid19 cumulative cases](/assets/covid19_0.02>0.01.png)
![covid19 cumulative cases](/assets/covid19_0.03>0.02.png)
![covid19 cumulative cases](/assets/covid19_0.04>0.03.png)
![covid19 cumulative cases](/assets/covid19_0.05>0.04.png)

