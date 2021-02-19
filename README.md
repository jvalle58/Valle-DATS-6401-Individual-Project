# The G20: A Military, Educational, and Healthcare Perspective

Welcome! You are now browsing at a visual presentation analyzing a select number of countries who are members of the G20 forum. The data assembled covers the following nations: Australia, Brazil, China, France, Germany, Italy, Japan, Mexico, Russia, South Korea, the United Kingdom (UK), and the United States (US). Over the course of this presentation, you will have the opportunity to explore these nations' trends in military, education, and healthcare spending from 2013 to 2017, and grasp at these variables' relationships with their respective economies.

## Preparing Our Data

Our data for GDP, population, and military and healthcare spending from 2013 to 2017 can be found at the World Bank's Indicator files. Figures representing the educational shares of GDP were located at several other sources. While China's figures were posted on Statista, the US reported its current educational expenditures at the Federal Reserve Bank of St. Louis' Economic Data page, which were then used to calculate its GDP shares over our timespan of interest. As for the other countries in our study, their shares were reported from the data site Knoema. 

Regarding the latter, as an important sidenote, Japan and South Korea's educational shares were missing in 2015 and 2017, respectively. Thus, during the data cleanup stage, these were adjusted by calculating the means for the other four years that already included figures for both countries. 

The Jupyter Notebook outlining the process of cleaning up the data prior to being exported to Excel and Google Sheets is available for you to view.

## Background

For a little background, let's report on the rates of GDP and population growth among the nations listed between 2013 and 2017.

### Rate of GDP Growth across the G20 Forum (2013 - 2017)

![image24](/images/image24.png)

As shown by the green geographic chart, the majority of countries actually saw their economies decline over our timespan. However, the three outliers - China, South Korea, and the US - expanded at relatively high rates, at 28.63%, 18.46%, and 16.29%, respectively. Note as well how four European countries - France, Germany, Italy, and the UK - shrank at some level between 1% and 8.50% from 2013 to 2017.

### Rate of Population Growth across the G20 Forum (2013 - 2017)

![image25](/images/image25.png)

Every country except Japan witnessed a rise in its population over our timespan. Taken alongside our findings for the growth rates of GDP, we can deduce that the GDP per capita in most nations shrank from 2013 to 2017. This is likely the case with Australia in particular, whose economy declined by more than 15% despite its population rising by more than 6%.

## The G20 Forum and their Militaries from 2013 to 2017

One of the conditions for a country to maintain a strong national security is often a potent and innovative defense establishment, whether its bases are at home or abroad. Defense financing remains a high consideration for many nations as they remain on the lookout for any impending threats to their security, as globalization pervades their economic priorities. However, this does not imply that military spending is necessarily a mandatory component of a national budget. In fact, many countries posess wide discretion as to how much funds are allocated toward military development. This takes into consideration the impact of other sectors or programs that may constitute mandatory spending. Nevertheless, even where defense financing is categorized as discretionary, it's not surprising that nations may prioritze it, over other discretionary funding sources, while outlining their budgets.

### Analyzing Military Spending Annually and as a Share of GDP

![image1](/images/image1.png)

![image2](/images/image2.png)

Right away, we can tell that the US and China spent the most, on average, on their militaries from 2013 to 2017, partly on account of the fact that the two possessed the largest economies in the world over that timespan. When we pivot toward the countries' mean military shares of GDP however, as shown in the orange bar chart, Russia emerged on top at 4.50%, almost a full percentage point ahead of the US. China on the other hand reported the fourth-highest average at 1.90%.

Yet, national figures on military spending alone do not tell the whole picture on the ramifications they bring toward their respective economies. To address this, let's now consider the role of population. Using this variable, we can determine the countries' GDPs per capita, and extend our inquiry toward identifiying how much they spent on their militaries per capita. The bubble chart below presents the countries' figures for 2017, but the other years in our timespan can also viewed from its corresponding HTML file.

### Relationship Between Military Spending Per Capita and GDP Per Capita

![image3](/images/image3.png)

The diameter of a bubble is affected by the extent of its corresponding country's population, while its color indicates its geographic region. In fact, China was the only country in the G20 to report a population of more than a billion from 2013 to 2017. Furthermore, a notable shift occurs in Australia over our timespan. While it reported a GDP per capita of almost $70,000 early on in 2013, that figure declined to just below $55,000 in 2017, despite its military spending per capita staying relatively stagnant. Additionally, outside of Russia, the other four European countries - France, Germany, Italy, and the UK - posted GDPs per capita of more than $30,000 annually. Yet, they also spent less than $1,000 on their militaries per capita every year. Based on this observation, they likely allocated a larger portion of their annual budgets toward other forms of discretionary spending.

### Change in Absolute Military Spending across the G20 Forum (2013 - 2017)

![image4](/images/image4.png)

The geographic chart shown above presents the changes in absolute military spending throughout each nation from 2013 to 2017. Only three countries, Australia, China, and South Korea, witnessed a rise in that category over our timespan. In China's case, it reported an increase of $48.59 billion, far surpassing the rest.

### Change in Relative Military Spending across the G20 Forum (2013 - 2017)

![image5](/images/image5.png)

Darker shades of orange in this geographic chart indicate higher relative rates of military spending, while lighter shades indicate lower rates. When analyzing this, China again comes out on top, at a substantially high 27.01%. With regards to Australia and South Korea, they saw their defense budgets increase by 11.54% and 14.16%, respectively. As an intriguing side note, although Russia reported the highest average share of GDP toward its military over our timespan, its relative rate of spending in that category actually dropped the quickest, at almost a quarter from 2013 to 2017.

## The G20 Forum and Education from 2013 to 2017

For this project, education expenditures refer to any funds spent by a national government toward both public and private schools. Given the varying degree between countries with respect to their level of central authority on managing education, the amount spent toward education may depend on the ability of individual precincts to shape their local educational standards. This may especially be the case with regard to public schools, which in some nations may apply a single standard of essential subjects throughout their surrounding areas. Educational spending may also be affected by what topics are taught to students, as some specialties may gain greater traction and prevalence in the labor force as ever-evolving economic trends present themselves to workers amid globalization. These observations, however, should not imply that a rise in educational spending necessarily correlates with higher academic performance in a country.

### Analyzing Educational Spending Annually and as a Share of GDP

![image6](/images/image6.png)

![image7](/images/image7.png)

The first chart above demonstrates how the US and China spent the most on education in absolute terms compared to the other countries. But when we rank the G20 in terms of mean share of GDP toward education, Brazil takes the top slot at 6.13%. The US, in contrast, places sixth at just less than 5%.

This latter note further underscores how the relative size of an economy can significantly impact how much of its national budget is allocated toward sectors like education. Under this sector, it also weakens the notion of a significant relationship between spending and share of GDP. Similarly as before however, we can take our investigation a little bit further by accounting for population. Do the trends with respect to GDP per capita and military spending per capita apply to education as well?

### Relationship Between Educational Spending Per Capita and GDP Per Capita

![image8](/images/image8.png)

Compared with military spending per capita, there is an even stronger and more positive correlation between educational spending per capita and GDP per capita. We can pick up yet again over our timespan how the US eventually overtook Australia based on its GDP per capita. Looking back at France, Germany, Italy, and the UK, they consistently spent more than $1,000 per capita with respect to education, further underlining how they allocated a greater portion of their respective GDPs toward that rather than their militaries. China, on the other hand, spent less than $400 per capita on education every year from 2013 to 2017, owing to the effect of its significantly larger population.  Similarly as earlier, the bubble charts for the other four years evaluating this relationship are available inside this GitHub repository.

### Change in Absolute Educational Spending across the G20 Forum (2013 - 2017)

![image9](/images/image9.png)

In varying shades of gray, we can observe the changes in absolute educational spending among the nations. The only ones to increase their spending over our timespan were the US, China, and South Korea. Taking the former two together, these augmented their spending by almost 10 and 11 times, respectively, the amount as South Korea from 2013 to 2017.

### Change in Relative Educational Spending across the G20 Forum (2013 - 2017)

![image10](/images/image10.png)

The darker the shade of yellow here, the greater the relative change in educational spending from 2013 to 2017. Looking at it from this angle, while China increased its spending at a faster rate than the other countries (28.01%), South Korea's rate (13.44%) actually exceeded the US's (10.85%). We should also take note of Australia's shift in that sector over time. Given that its educational spending per capita declined from more than $3,500 in 2013 to less than $2,800 in 2017, at more than 17% its relative educational spending declined the most out of all countries in our list.

## The G20 Forum and Healthcare from 2013 to 2017

Unlike military and educational spending, healthcare in many areas often constitutes a mandatory component of annual spending. Similarly as with education, the amount of authority a nation's government possesses on administering healthcare can determine how much priority it receives in budgeting. The influence of private-sector companies in insurance, pharmacology, and other related healthcare industries may also be considered.

### Analyzing Healthcare Spending Annually and as a Share of GDP

![image11](/images/image11.png)

![image12](/images/image12.png)

While the US and China again posted the highest average figures in healthcare spending for each year, the difference here is more significant than with military and educational spending. Based on the combo chart shown above, the US on average ($3,030.33 billion) spent almost six times the amount as China ($537.07 billion) on healthcare. This distinction becomes even more apparent when we analyze the countries' mean shares of GDP. In fact, more than the rest of the G20, the US spent a greater average portion of its GDP (16.68%) toward healthcare, while China's share represented the smallest (4.90%) out of our list. Hence, the US's mean share was calculated as almost four times the size of China's, despite the fact that the two possessed the world's largest economies over our timespan.

As a separate inquiry, does this difference likewise hold when comparing the countries' GDPs per capita with the amounts they spent on healthcare per capita?

### Relationship Between Healthcare Spending Per Capita and GDP Per Capita

![image13](/images/image13.png)

The bubble chart here demonstrates China, Mexico, and Russia each spending less than $1,000 on healthcare per capita in 2017, as was also the case over the rest of our timespan. This is an extension from the red bar chart shown above indicating that these countries reported the lowest mean shares of GDP toward healthcare. At the same time, we should note that Brazil did briefly spend more than $1,000 on healthcare per capita in 2014, but dropped back under that amount along with the other three. On a separate note, Australia's healthcare spending per capita dropped by almost a quarter from 2013 ($5,970.74) to 2016 ($4,597.70), before finishing at $4,973.52 in 2017. The US, in contrast, shifted rightward from about $8,600 in 2013 to more than $10,200 in 2017. Based on these observations, we can deduce there is somewhat of a stronger relationship between the mean share of GDP toward healthcare in a country and its spending per capita within that sector compared to military and educational spending.

### Change in Absolute Healthcare Spending across the G20 Forum (2013 - 2017)

![image14](/images/image14.png)

Of the countries included in this presentation, four posted a rise in absolute healthcare spending between 2013 and 2017 - China, Germany, South Korea, and the US. The US's figure was especially significant in that it was more than three times ($598.01 billion) the amount as China's ($183.36 billion). We should also point out there is some discrepancy among the four regarding the relationship between their increases in healthcare spending and their average shares of GDP toward it. While the US and Germany respectively reported the highest and third-highest average shares, South Korea and China placed in the bottom four with respect to that variable.

### Change in Relative Healthcare Spending across the G20 Forum (2013 - 2017)

![image15](/images/image15.png)

Although the US's healthcare spending rose more in absolute terms than China's, the latter's rise was actually greater in relative terms, at more than 40%. South Korea's increase (34.75%) likewise outpaced the US's (21.98%). Germany's rate on the other hand was significantly more muted, seeing its relative spending rise by just 1.62%.

## Case Study: Comparing China and the United States

At this point of our visual presentation, we now turn to a special case study focusing on the two biggest spenders for each of the aforementioned categories - China and the US. Considering how these two countries possessed the largest economies in the world over our timespan, it should not come as a surprise that they likewise spent the most. However, we can examine them even further by isolating their figures from the other countries included in our data. In doing so, we can elucidate any intriguing intra-year trends with respect to their spending habits and economic compositions. From there, we will be able to make several instrumental predictions on what their future budgets may entail, while taking into account the latest national developments reported by the news media within both countries.

### A Side-By-Side Examination of the Two Countries

To start, let us pivot back to GDP. Recall that China and the US reported greater GDPs than the other countries for each year, as well as higher rates of economic growth over our time span. But just how much did they grow in between years?

![image16](/images/image16.png)

![image17](/images/image17.png)

Clearly, the US continues to exhibit a larger economy overall than China. But we should also note that China's economy between 2013 and 2014, as well from 2016 to 2017, actually expanded more than the US's in absolute figures. This observation becomes even notable when we analyze the rates at which both countries' GDPs are growing over time. In fact, as we can see from our area chart, China out-paced the US in terms of GDP growth in three of the four year transitions. This indicates that the gap between the size of both countries' economies is shrinking as time passes. However, does this relationship extend to when we study their trends in military spending?

![image18](/images/image18.png)

![image19](/images/image19.png)

When comparing the two with respect to military spending, the four charts shown above imply an even greater shrinking of the gap with respect to that variable. Unlike the other countries we studied earlier, China was the only one to never lower its military spending between years, as can be noted by the charts on the right. This explains why its rate of spending substantially exceeded the rest in that category. Looking at it from another perspective, while the US spent more on its military in absolute terms than China, its military share of GDP declined from 4.05% to 3.31% over time, while China's stayed consistently at just less than 2% each year. However, the former's relative military spending did turn positive between 2015 and 2016, albeit by less than 1%. Note that in that same year transition, China's relative spending slowed to almost the same rate as the US's.

![image20](/images/image20.png)

![image21](/images/image21.png)

If we turn our case study toward an educational angle, one observation we can pick up right away is that spending in that sector never dropped between years within both countries, in contrast to military spending. On that note though they have seen declines in their shares of GDP toward education. Yet again, China allocated a proportionately greater amount of funds toward education than the US for most of the year transitions. The time encompassing 2015 and 2016 is an intriguing outlier, as the US absolutely grew its educational spending at almost ten times the amount as China then. Similarly as with our inquiry on military spending, China's relative spending toward education exceeded the US's for a larger portion of time.

![image22](/images/image22.png)

![image23](/images/image23.png)

Compared to the other variables, the US's absolute figures in healthcare spending dwarfed China's at an even greater scale. Recall as well that China on average reported the smallest share of GDP toward healthcare of all the countries on our list, further underlining this gap. In fact, for each year it spent more than five times as much as China in that sector, especially in 2013. While the gap between the two is significantly larger under this category, when we look at the changes in healthcare spending between years, the gap is somewhat smaller from 2016 to 2017. Additionally, China's relative spending toward healthcare rose by more than 13% from 2016 to 2017, after declining in the previous years of our time span. The US's relative spending likewise dropped somewhat from 2014 to 2017. Regarding the latter, given its relatively high shares of GDP toward healthcare compared to China, at more than 16%, this observation further demonstrates how military spending there was prone to greater fluctuations between years.

### Predictions

We should first consider how China over our timespan gradually closed the gap between it and the US with respect to military spending. Therefore, it's possible that the latter may augment its spending to a greater level in subsequent years to maintain that gap, owing to the impact of the trade war between both nations and the erosion of their relationship amid the spread of COVID-19. However, the size of the US's military budget will also depend on how much its foreign policy approach evolves as a result of the 2020 presidential election. Given these observations, it's unlikely that China will slow down its relative military spending any time soon. If the rate at which it spends increases to a scale that is large enough, its share of GDP toward defense may ultimately break 2% within the next ten years.

On the question of education, there is less likely to be a major closing of the gap, given how the two nations were somewhat closer to each other with respect to their changes in absolute spending between years, and their relatively declining educational shares of GDP. Although globalization may play a role behind any spending rises within this sector, we should also account for COVID-19. Much of the economic ramifications from the virus that have drawn attention as of late revolve around education, particularly the transition from in-person to online learning. As there continues to be debates, especially in the US, on whether or not to open schools, the administration of online education will probably assume a greater portion of both China and the US's annual budgets. School districts with significant outbreaks or historically weaker academic performance may also draw further consideration.

Not surprisingly, COVID-19 could also spur both nations to raise their relative healthcare spending, as this will become more critical for individuals who contract the virus. Besides the virus itself though, the effects of economic decline at home and abroad will continue to present other kinds of health problems. Such issues may include depression, anxiety, and stress, all of which have exacerbated since the virus's emergence. Thus, greater healthcare spending in the US and China will likely focus on expanding the resources necessary toward addressing the virus itself, including vaccination procedures, and helping patients with the aforementioned mental problems. As a consequence, while the US will likely maintain the top spot among the countries we have studied in terms of its mean share of GDP toward healthcare, China's share for that sector could continue rising somewhat steadily.

## Conclusions

When accounting for military, educational, and healthcare spending, national economic growth or decline alone cannot sufficiently explain movements within any of the sectors over time. In fact, a country may shift its spending from one sector to another in light of surrounding economic conditions, at home and abroad. Discretionary spending especially may decline amid recession, inclining a country to focus on mandatory funds.

A country's level of spending within a sector does not necessarily correlate with the share of GDP toward that sector. This observation emphasizes how the size of a country's economy can affect how much it can afford to transfer funds from one sector to another. Additionally, it further delineates the distinction between absolute and relative spending. The latter figure may more accurately describe spending shifts over time by accounting for a national economy's size on a proportionate scale. This is especially the case with regard to healthcare spending. As we saw earlier, the US spent more in absolute terms than the other countries on healthcare each year, and by extension reported the greatest such shift between 2013 and 2017. It also posted the greatest mean share of GDP toward healthcare over our timespan. Yet, China almost doubled the US's figure in terms of its relative shift in healthcare spending. This happened despite the fact that the US spent more than five times the amount as China on healthcare each year.

Similar disparities occurred with respect to military spending. While the US spent more on its military absolutely than the other countries each year, its funds actually declined from 2013 to 2015. Furthermore, it reported the greatest absolute decline from 2013 to 2017, despite maintaining the second-highest mean share of GDP. Regarding the latter observation, Russia posted the greatest mean share of GDP toward its military. However, partly on account of the fact that its economy shrank the most out of the countries included in this presentation, its relative military spending dropped the most from 2013 to 2017. China in contrast reported the greatest increases under both figures. Notably, it was one of only three countries, alongside Australia and South Korea, to augment its defense budget over time.

When comparing the countries from an educational perspective, per capita spending in that sector possessed a stronger correlation with GDP per capita than the other sectors. The fact it was so closely related with GDP per capita is quite significant when considering the long-term ramifications this can present for innovation and labor advancement. Economic growth in the educational sector is especially beneficial for families as they can more easily access any necessary resources that help them advance more easily within the labor force, using the skills acquired through schooling. Although a rise in educational spending per capita may present wider opportunities within the labor market, we should not automatically assume this will improve academic performance. According to the 2018 Program for International Student Assessment (PISA), six countries outperformed the US on their average cumulative score of reading, mathematics, and science. This occurred despite the US being the biggest annual spender on education for each year, as well as spending the most on education per capita in 2016 and 2017. Hence, transfering funds toward certain specialties or improving individual school performance may be more economically beneficial for families than raising spending all across the board.

This project was a tremendous first opportunity to get accustomed with Google API's visualization tools, and gain new insights about the G20's trends in military, educational, and healthcare spending from 2013 to 2017. References for this project are listed below.

## References

[Link to Google Sheets data](https://docs.google.com/spreadsheets/d/1Ig9G4lXtKgSdBzU0NNRTALwu5cebPNdkeYjgxh98U2M/edit#gid=1568021285)

Current health expenditure (% of GDP) | Data. (n.d.). Retrieved January 29, 2021, from https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS.

GDP (current US$) | Data. (n.d.). Retrieved January 29, 2021, from https://data.worldbank.org/indicator/NY.GDP.MKTP.CD.

Government current expenditures: Education. (2020, November 4). Retrieved February 3, 2021, from https://fred.stlouisfed.org/series/G160291A027NBEA.

How can I use the apply() function for a single column? (2020, November 2). Retrieved February 4, 2021, from https://stackoverflow.com/questions/34962104/how-can-i-use-the-apply-function-for-a-single-column.

How to drop unnamed column in Pandas? 5 Steps Only. (n.d.). Retrieved February 4, 2021, from https://www.datasciencelearner.com/drop-unnamed-column-pandas/.

How to Export Pandas DataFrame to an Excel File. (2020, July 1). Retrieved February 4, 2021, from https://datatofish.com/export-dataframe-to-excel/.

List of G20 Members. (n.d.). Retrieved January 29, 2021, from https://www.worldatlas.com/articles/g20-members.html.

Military expenditure (% of GDP) | Data. (n.d.). Retrieved January 29, 2021, from https://data.worldbank.org/indicator/MS.MIL.XPND.GD.ZS.

PISA 2018 Worldwide Ranking - average score of mathematics, science and reading. (n.d.). Retrieved February 17, 2021, from https://factsmaps.com/pisa-2018-worldwide-ranking-average-score-of-mathematics-science-reading/.

Public spending on education as a share of gross domestic product (%). (n.d.). Retrieved January 30, 2021, from https://knoema.com/atlas/topics/Education/Expenditures-on-Education/Public-spending-on-education-as-a-share-of-GDP?action=export&gadget=tranking-container.

Remove index name in pandas. (2018, February 16). Retrieved February 4, 2021, from https://stackoverflow.com/questions/29765548/remove-index-name-in-pandas.

Schleicher, Andreas. (2018). PISA 2018: Insights and Interpretations. Program for International Student Advancement.

https://www.oecd.org/pisa/PISA%202018%20Insights%20and%20Interpretations%20FINAL%20PDF.pdf.

Textor, C. (2020, November 19). Public expenditure on education as a share of gross domestic product (GDP) in China from 2009 to 2019. Retrieved January 30, 2021, from https://www.statista.com/statistics/1113951/china-public-education-expenditure-as-a-share-of-gdp/.
