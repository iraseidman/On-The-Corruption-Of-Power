# Ira Seidman's GA DSI Capstone Project - On The Corruption Of Power
---
## Problem Statement
It is clear from headlines and poling data that government is not functioning the way it should - it is often both unpopular and under-delivers as far as outcomes are concerned. The question this project seeks to answer is are there indicators of corruption and if so can a government's level of corruption be predicted. If indeed it can be, governmnets in most need of intervention could be identified ahead of time and the model itself could likely help inform mitigation strategies. The crux of this project is determining how we can predict levels of political corruption by looking at a government strucuture and outcomes.

## Executive Summary
After collecting data from a wide variety of sources including the UN Development Program, University of Groningen, World Bank, and the Gallup World Happiness Report, a model was constructed that was able to explain over 25% of variance seen in how corruption is viewed around the world. There is room for improvement with this model, but it offers interesting preliminary views into how political corruption can be addressed; these solutions include but are certainly not limited to - strengthening the economy, creating a more free society, and prioritizing happiness. With this insight and model, we can begin to take on an issue that has been pervasive throughout history and hopefully begin to curtail some of the most egregious abuses of power.

## Analysis
Initial exploratory data analysis found strong correlations between less corruption and a better economy, freedom, and happiness. Other strong correlations existed between life expectancy and gdp per capita along with time spent in school. The best model itself used principal component analysis which may have been necessary given how different all of the features were (please see the data dictionary below).
           
## Data Description
The data utilized for this project came from Our World In Data and Kaggle. From these sources data from a variety of other sources was merged into one dataframe (please see below for the URLs). Please see the data dictionary below:

| Feature Name | Description |
|    -----     |   -------   |
| country | 148 Rows of data for countries all around the world |
| life_expectancy | How long does the average person in this country live for (years) |                       |
| gdp_per_cap | How much does the average citizen make in a year (adjusted for price differences between countries) |
| average_years_of_school | How many years in school did the average adult spend in this country |
| total_population| How many people live in this country |                 
| auto_demo | How does this country's government compare on a scale from -10 to +10 where -10 is autocracy and +10 is relatively free elections |   
| happiness | How happy are the citizens as determined by millions of interviews |
| freedom | How free are the citizens of this country |
| less_corruption | How much does the government obstrut people's lives |    

**Data Sources**
###### https://ourworldindata.org/democracy
###### http://hdr.undp.org/en/indicators/103006
###### https://www.rug.nl/ggdc/productivity/pwt/
###### http://hdr.undp.org/en/indicators/103006
###### https://www.kaggle.com/unsdsn/world-happiness

## Conclusions and Recommendations
I recommend getting more data as both columns and rows to better train the model to understand how decentralizing power may effect the public's view on political corruption. Though this data may not exist widely on an international scale it could very valuable to begin an effort to procure this type of data, or at potentially scale the model down to a level where the data may already be avaialble. This project has discovered preliminary insights into sources and indicators of corruption but there is still much more work to do to truly understand and get to a point where political corruption can be effectively mitigated.