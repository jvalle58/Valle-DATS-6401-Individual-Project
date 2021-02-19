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
