# An exploration of factors affecting life expectancy in world countries
## by David Mullen


## Dataset

> The bulk of the data for this study was acquired from 4 tables acquired from Gapminder.org, augmented by two important additional data types - the continent that the country is a part of, and the presence or lack of universal healthcare. This data was gathered from the relevant Wikipedia pages. A single year was selected for this study, based on maximization of availability of data (i.e. the lowest number of missing data points), between 2005 and 2015. The year determined to be best for this study is 2009.

> Data wrangling for this set included joining all tables, which in the case of our set included joining on country names as taken from multiple sources. This required string matching, and then in both cases a few countries had to be matched by hand based on different spellings, etc.

> The cleaned and merged data was then stored in a csv file which is used to make the slides.


## Summary of Findings

> Life expectancy has a right shifted distribution, and varies by a roughly a factor of 2 between countries. This study includes a mix of continents and about a 60-40 mix of healthcare type. Income, healthcare spending, healthcare type, and continent all are predictive of life expectancy. Population of the given country does not clearly predict life expectancy. Healthcare spending per capita and income per capita are similarly predictive. Both have a logarithmic curve and a bimodal distribution. 

## Key Insights for Presentation

> Continent and healthcare type are predictive of life expectancy separately and together
> Income and healthcare spending are similarly predictive of life expectancy, and income is also predictive of healthcare type.