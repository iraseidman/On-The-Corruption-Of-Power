# On The Corruption Of Power
---
## Problem Statement
It is clear from headlines and poling data that government is not functioning the way it should - it is often both unpopular and under-delivers as far as outcomes are concerned. The question this project seeks to answer is are there indicators of corruption and if so can a government's level of corruption be predicted. If indeed it can be, governmnets in most need of intervention could be identified ahead of time and the model itself could likely help inform mitigation strategies. The crux of this project is determining how we can predict levels of political corruption by looking at a government strucuture and outcomes.

## Executive Summary
After collecting data from a wide variety of sources including the UN Development Program, University of Groningen, World Bank, the Gallup World Happiness Report, World Population Review, and the CIA a model was constructed that was able to explain over 46% of tge variance seen in how corruption is viewed around the world. There is room for improvement with this model, but it offers interesting preliminary views into how political corruption can be addressed; these solutions include but are certainly not limited to - strengthening the economy, creating a more free society, and prioritizing happiness. With this insight and model, we can begin to take on an issue that has been pervasive throughout history and the world and hopefully begin to curtail some of the most egregious abuses of power.

## Analysis
Initial exploratory data analysis found strong correlations between less corruption and a better economy, freedom, and happiness. Other strong correlations existed between life expectancy, geographic denity and a few other features to a lesser extent. The best model itself used principal component analysis with a rando forest model which though statistcal inference cannot be drawn from this model it is able to predict nearly half of the variance bewteen the outcomes observed and the mean (with an r squared score of .463)
           
## Data Description
The data utilized for this project came from Our World In Data, Kaggle, the University of Groningen, the United Nations, World Population Review, and the CIA. From these sources data was merged into one dataframe, please see the data dictionary below:

| Feature Name | Description |
|    -----     |   -------   |
| country | Country identifier for 126 different nations|
| population | 126 rows of population data for countries around the world |
| area_square_km | 126 rows of area geographical data for countries around the world |
| density_square_km | 126 rows of area density data for countries around the world |
| average_years_of_school | 126 rows of average length of time spent in school data for countries around the world |
| auto_demo_polity | 126 rows of polity data (-10 being strict autocracy and +10 being strict democracy) for countries around the world |
| gdp_per_capita | 126 rows of gdp per capita data for countries around the world |
| happiness_index | 126 rows of happiness index data for countries around the world |
| freedom_index | 126 rows of freedom index data for countries around the world |
| less_corruption_index | 126 rows of corruption index data (the higher the less corrupt) for countries around the world |
| life_expectancy | 126 rows of life expectancy data for countries around the world |
| inequality_gini | 126 rows of wealth inequality data for countries around the world |
| median_household_income_dollars | 126 rows of median household income data for countries around the world |
| median_per_capita_income_dollars | 126 rows of median per capita income data for countries around the world |
| median_individual_income_dollars | 126 rows of median individual income data for countries around the world |  

**Data Sources**
###### https://ourworldindata.org/democracy
###### http://hdr.undp.org/en/indicators/103006
###### https://www.rug.nl/ggdc/productivity/pwt/
###### http://hdr.undp.org/en/indicators/103006
###### https://www.kaggle.com/unsdsn/world-happiness
###### https://worldpopulationreview.com/country-rankings/median-income-by-country
###### https://worldpopulationreview.com/
###### https://www.cia.gov/the-world-factbook/field/gini-index-coefficient-distribution-of-family-income/country-comparison

## Conclusions and Recommendations
To better unDerstand how decentralizing power may effect the public's view on political corruption there may be more demographic data by nation along with slightly more advanced models that can be used. Though this data may not exist widely on an international scale it could very valuable to begin an effort to procure this type of data at a more local level like by US state or cities. Even so there are clear connections between perceived corruption and financial indicators as improved economic outcomes are strongly aligned with the corruption index (with the freedom and happiness indexes closely trailing). These preliminary insights into sources and indicators of corruption are helpful but there is still much more work to do to in order to understand and get to a point where political corruption can be effectively mitigated.