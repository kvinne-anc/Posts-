![Market1](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/farmers-markets.jpg)

# Economic Accessibility of Farmer's Markets in New York State 
## A geospatial analysis of the distribution of Farmer's Markets in New York State and their accessibility to low-income families

"Farmers markets are an important way for citizens to eat healthy fresh food while supporting small family farms. 
This data contains information about all the registered farmers markets in the United States in 2020. This includes the city, 
county, lat and long, and information about the types of food sold at each market. 
One criticism of farmers markets is that they are largely inaccessible to many Americans, especially those of low socio-economic status. 
Does the data reflect this criticism?"


This analysis attempts to discern how accessible Farmer's Markets are to lowest economic bracket of Americans. It has long been argued that 
those who are at an economic disadvantage and must rely on food stamps and other forms of nutritional benefit programs are more likely to eat 
unhealthy food. As such, they are disproportionately affected by obesity, high blood pressure and diabetes.

It has been argued that this is due, in large part, to the inaccessibility and affordability of healthy, organic, or locally produced food. 
For a time, this could be attributed to the nature of Farmer's Markets as open-air, relaxed settings, largely devoid of methods for accepting electronic payments. 
In 2009, a study shows that only 900 out about 5,000 Farmer's Markets accepted food benefits. In 2020, that number has grown exponentially. This may very well be attributed the 
emergence of technology that makes accepting electronic payments convenient, such as CUBE or Stripe. 

![Banner](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/SFMNP_Banner.jpg)

For this particular analysis, the focus centered on Farmer's Markets across New York State, and the distirubtion of markets that accept various forms of benefits.
Markets were geospatially mapped by longitude and latitude to demonstrate their spread. Although other information was included in the dataset, such as city, zipcode, 
and occassionally an address, longitude and latitude served to be the best identifiers here. While the coordinates ensure accuracy of location, they do present difficulties
when subjected to the process of graphing data. 

## The distribution of markets in New York State can be seen in the plot below, which shows the distribution of credit as an accepted form of payment. 
The color distribution has been used to indicate each form of payment's status as accepted (yellow) or not (blue). Credit can be viewed almost as a control, although not entirely. 
Credit is a much more common form of payment in general, although many Farmer's Markets still opperate in a strictly cash environment. The significance of the acceptance of credit 
is that it suggests that the vendors have the means to process benefits payments, such as the EBT food stamps debit card.

![Credit](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_Credit.png)

Aside from credit, four other payment methods were mapped: WIC (Women, Infants, and Children), WICcash (Women, Infants, and Children cash benefit), 
SFMNP (Senior's Farmer's Market Nutrition Program), and SNAP (Supplemental Nutrition Assistance Program), each of which is a separate benefits program. 

## The distribution of each can be seen below, in order from most widely accepted to least: 

# Women, Infants, and Children
![WIC](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_WIC.png)

# Senior's Farmer's Market Nutrition Program
![SFMNP](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_SFMNP.png)

# Supplemental Nutrition Assistance Program 
![SNAP](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_SNAP.png)

# Women, Infants, and Children cash benefit
![WICcash](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_WICcash.png)

As evidenced by the geospatial map of the payment data, the acceptance of benefits is relatively evenly distributed in relation to the prevalence of Farmer's Markets. 
As expected, the prevalence of markets is clustered near cities, with the highest density being unsurprisingly in New York City, and then there is a spattering of 
markets in more rural areas as well. The dense clustering that appears to go straight across the middle of the state from East to West encompasses Albany, Utica, 
Syracuse, Rochester and Buffalo. 

## The simultaneous representation of all five payment methods and their acceptance, with the upper layer depicting acceptance and the lower non-acceptance:

![AllFM](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/test.png)

The data presented here shows that mulitple markets are clustered around the same locations and there is a relatively even distribution of markets that accept benefits and 
markets that don't. Given this resut, it is safe to say that the accessibility of Farmer's Markets to economically disadvantaged people is strong, and will likely grow stronger. 
In order to accept benefits as payments, markets must register and become licensed by the Food and Nutrition Service (FNS) to accept benefits. 

## This Kernel Density Plot below shows the binary representation of the accepted to not-accepted ration of each payment method:

![KDE](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farm_KDE.png)

Accepting benefits is on the rise due in part to the availablity of techonology that makes electronic payment processing easy and convenient, as well the added market share 
that it provides access to. It provides low-income people with more options for affordable, healthy food, and it serves to support local farms and producers. 
Overall, it's really a win-win. 

![Market3](https://github.com/kvinne-anc/kvinne-anc.github.io/blob/master/Farmer's%20Market.jpeg)


Data sourced from: 
- [Kaggle](https://www.kaggle.com/madeleineferguson/farmers-markets-in-the-united-states)

Notebook: 
- [Colab](https://colab.research.google.com/drive/1qGAg_zSVG1Lu903jGCGS3rIO2CQRNhP2?usp=sharing)

## Date published: June 25th 2020 
