<html>
<body>
<h1 align="center">At least the decline in quality of life is there...</h1>
  
<h3 align="center">Random Forest Model</h3>
  
<h5 align="center">What is it?</h5>
  
<p>The Random Forest Model is a machine learning model that is a type of ensemble model(in ensemble models, machine learning models are combined to make a
stronger model). The Random Forest Model combines many decision trees for an accurate prediction. I will get into decision trees, but first, I want to talk
about overfitting. Random Forest Models are prone to overfitting, which is why there is a number for max_depth, as it will prevent overfitting. Overfitting
basically means that a model does well with the training data, however, because it does so well to the training data, it is unable to adjust to more real world
data. This is why I am limiting max_depth, as limiting max depth allows for a limit on complexity, and by extension, overfittng. Below, I will have a detailed
description of Decision Trees.</p>
  
<h5 align="center">What are Decision Trees and how do they work?</h5> 

<p>Decision trees are a type of AI/Machine Learning algorithm that aims to learn how the data works by creating partitions. Decision trees are a popular
alternative to Neural Networks and Deep Learning, which are heavily used by colleges and the private sector(I won't complain, as they can take the
computational burden of a Neural Network, as they take up lots of computation power; they are essentially useless unless you have more than 100,000 data
points). This is the reason I chose Decision Trees, as they are essentially the knock-off "Neural Networks" that can accomplish similar feats without
putting a huge burden on the computer and is fairly accurate with the amount of data I have(a neural network will just be wrong, unless I have more data).
Anyway, decision trees create partitions in data that follow a certain pattern: when x is greater than 5, y does this. It isn't that simple,
but it is good enough to get a basic enough idea. With decision trees, entropy, or the variance of the data set as the result of a partition, looks at
the variance and tries to minimize itself(again, oversimplified). The partition that has the least entropy is made by the decision tree. The partitions
will keep on happening until the entropy is zero. However, as I put a limit on the variable max_depth, it can't do that. The problem with letting entropy 
fall to zero is that it leads to overfitting: it fits the training data so well that it can't be used to analyze other datasets. Anyway, I should stop
rambling about decision trees so that you can read about the data and the projection(you might call me a prophet of doom after you read, so read with
caution).</p>

<h3 align="center">Original Data and Projection</h3>

<p>Below is the graph of the collected data(growth rates are not included) for you to see.</p>

![image](https://user-images.githubusercontent.com/48994987/216841731-824daa99-e424-406c-a543-19ca65201550.png)

<h5 align="center">Immigration</h5>

<p>Immigration, a hotly conested issue in this country. But before diving into the data, I want you to remember what I said last time I did a prediction about
America's "future"(1970s onward was the future, just wanted to test my model). I said that immigration might be a stable cycle to work from when it comes to 
America's future. While I wasn't very clear then, I certainly have the graph now. As you can see on the graph, Immigration appears to be a somewhat stable
cycle to work off of. The cycle sees an increase in the first 50 years. Think about the time till Trump: there was very little backlash against immigration
for the most part and the people who were against it didn't hold the majority of power. There might've been some isolated times where there might've been 
anti-immigrant backlash(like 9-11), but the factions against immigration didn't hold much power in the government, at least until Trump(I am only talking
about the 21st century so far). That's where we are. However, its been a little over 50 years, and by the cycle, there should've been a civil war. Or maybe the
civil war was going to happen but then COVID came and united everyone(that sounds so crazy). However, when looking beyond a civil war and its underlying
characteristics, one thing that appeared in common was the mass polarization. So, maybe the civil war was a digital warfare campaign on social media(who knows
how wars are fought these days). Anyway, based of this seemingly stable cycle, we can infer that we are where America was at the start of the 1870s. That means
we are in the Gilded Age, an era of industrialization, isolationism, and reduced military spending(and hopefully a budget surplus this time) is coming. If I were to
tell you more about what else I think is going to happen, I would say that quality of life would say that there would be some mild anti-immigration laws that don't 
keep too many foreigners out, but they're also not too liberal with immigration. Also, I would say that a new form of economic organization would come through.
It could be more of an online economy, or maybe it could be a new revitalization of American industry. Now, I am sure that some of you are looking for the 
"prophet of doom" predictions(to be real though, no prophet of doom really writes paragraphs on his programming work). One prediction that might spell "doom"
(it may not be too bad, for some) is a new economic depression. If we are in a parallel version of the 1870s(because history repeats), then there would probably
be a recession that could be as bad as 2008. This could be a move to stabilize the currency, and with that the economy. The main problem in the 1870s were the
railroads as many were speculating in them to gain a market share. Even though the time to search for market share is over(most companies want profit NOW), I doubt
this is the case. However, one commonality is that the money supply to take out loans could be declining. As more Baby Boomers retire, there will be less money
that will be able to be loaned out, and so that could be where the crisis starts. An economic crisis does start with the contraction of the money supply, but 
that is also because the economy is so messed up that the only thing keeping it going are the infusions of cash. This is what could be happening, as the Baby
Boomers are a large generation, and as they retire, the smaller "saver" generation may not collectively save as much money as the Boomers did in order to 
keep the economy afloat. Who knows, we might see the "Panic of 2025" The economy is a place with investment abound, but without the money to support them, it
gets harder to keep our modern economy going. Like one railroad company started the Panic in 1873, a large tech company(maybe Apple?) could start the "Panic of
2025". Or maybe we are in the Panic of 1873 right now(it lasted for around 6 years in US by the way). But whatever we will face, I can tell you that we will come out
of this strong, like how America's navy came out of the 1890s as a rising star, eventually giving the Spanish a beating on Cuba and the Philippines(we do the same
to China maybe?).</p>

<a href="https://github.com/akhilmanhattan/big_projects/tree/main/artificial_Intelligence/Regression/DecisionTree/AmericaPrediction(1)/JupyterNotebook">
Last Time's Prediction(Turned into Alternate History)</a>

<h5 align="center">Tariffs</h5>

<p>Tariffs, at least in our modern world(as of February 6, 2023), are looked down. Everyone from the teachers in school, to the mainstream economists,
will tell you that tariffs are bad for the economy(to be clear, I am not going to say they are all wrong). However, could this belief in free trade 
diminish soon. As you can see, America has had high tariffs for most of its history, and when looking at historical tariffs, one could laugh at Trump's
tariff(they weren't that high when you consider the historical precedent). In case you're wondering, I did say tariffs are good for the economy in the 
short term, but you can't just just place tariffs the way you want. For example, tariffs in the 1880s was one factor that allowed for an increase in worker
benefits in the German Empire. Also, there is a difference in a country like America versus a country like Monaco when placing tariffs due to producing
power. Also, the Smoot Hawley Tariff went badly because now, there was absolutely no way that the US could trade with anyone. Tariffs were okay in the
1800s as the US wasn't that much of a major economy, however, as the US is more integrated and a larger player, the US can't go full on protectionist.
Also, when looking at the graph, you can see tariffs as reactions to something that was going on in society. For example, the 1920s and 30s saw increases
in tariffs to make sure a recession doesn't come. It did kick the can down the road, but the Great Depression was so bad that tariffs couldn't do anything
anymore. High tariffs was a characteristic of the reconstruction. DUring the Long Depression, the rise of protectionism helped to kick the can down the
road for World War 1(seriously, the Scramble for Africa was what delayed WW1 when comnined with the short term rise in living standards,and these were
reactions to the Long Depression). Considering what I said in the immigration section, and also how America isn't dependent on other countries for
its primary needs, America could become protectionist in the future, and maybe fight in WW3(probably not though, as there aren't the young
populations to do so anyway from around the world). However for now, just know that tariffs could be coming if what I said in the immigration section
turns out to be true(the fall of free trade happens when there appears to be a threat in the stability of the world).</p>

<h5 align="center">Sources</h5>

<a href="https://www.cdc.gov/nchs/data/statab/natfinal2003.annvol1_01.pdf">Birth Rate from 1909 to 1970</a>

<a href="https://www.statista.com/statistics/195943/birth-rate-in-the-united-states-since-1990/">Birth Rate from 1990</a>

<a href="https://www.statista.com/statistics/269967/urbanization-in-the-united-states/">Urbanization in America in 1970</a>

<a href="https://www.macrotrends.net/countries/USA/united-states/tariff-rates">Tariff rate from 1990</a>

<a href="https://www.migrationpolicy.org/programs/data-hub/charts/immigrant-population-over-time">US Foreign Born Percentage from 1970</a>

<a href="https://fraser.stlouisfed.org/files/docs/publications/histstatus/pages/1975-1979/58477_1975-1979.pdf">Tariff Rates from 1821 to 1970</a>

<a href="https://www2.census.gov/library/publications/decennial/1820/1820a-02.pdf">1820 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1830/1830b.pdf">1830 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1850/1850d/1850d-02.pdf">1850 Census(1)</a>

<a href="https://www2.census.gov/library/publications/decennial/1850/1850a/1850a-06.pdf">1850 Census(2)</a>

<a href="https://www2.census.gov/library/publications/decennial/1860/population/1860a-02.pdf">1860 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1870/population/1870a-28.pdf">1870 Census(1)</a>

<a href="https://www2.census.gov/library/publications/decennial/1870/vital-statistics/1870b-31.pdf">1870 Census(2)</a>

<a href="https://www2.census.gov/library/publications/decennial/1880/vol-01-population/1880_v1-07.pdf">1880 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1900/volume-1/volume-1-p3.pdf">1900 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1910/volume-1/volume-1-p4.pdf">1910 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1920/volume-3/41084484v3ch01.pdf">1920 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1930/population-volume-2/16440598v2ch10.pdf">1930 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1940/population-volume-2/33973538v2p1ch2.pdf">1940 Census</a>

<a href="https://www2.census.gov/library/publications/decennial/1950/population-volume-2/21983999v2p1ch3.pdf">1950 Census</a>

<a href="https://www2.census.gov/prod2/statcomp/documents/1961-02.pdf">1960 Census</a>

</body>
<html>
