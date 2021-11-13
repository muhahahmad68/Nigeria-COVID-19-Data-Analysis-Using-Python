# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

## INTRODUCTION
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus, and it has affected major parts of the world. Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its first case on 27th February 2020.Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.In this project ,I employ data science & analytics skills to collect data, explore the data, perform analysis, create visualizations, and generate insights

## DATA COLLECTION
I obtained data by performing web scraping on NCDC website. NCDC data contains four columns which include Lab confirmed cases, recovered cases, death cases and discharged cases.
I obtained Nigeria daily data from john Hopkins university center for Systems science and engineering GitHub repository. The repository originally consists of daily covid data across various countries in the world, I extracted from it that of Nigeria only. Three different dataset were obtained from john Hopkins repo.
I also worked with some downloaded dataset which includes GDP and Vulnerability index data, which ranks from low(0) to high(1+). 

## METHODS
Got my dataset from NCDC website using read html method of Pandas and extracted my data.
I used requests library to obtain my data from JHU CSSE.
Used read csv to obtain the given/downloaded dataset.
Conversion to appropriate data types.

## ANALYSIS
Top confirmed cases were from Lagos, FCT, Rivers, Kaduna and Pleatue. Top discharged cases follow same pattern for first 5 states. 
Top death cases are Lagos, Edo, Oyo, FCT.
Relationship between confirmed cases and discharged cases are linear until August 2021,when discharged cases dropped.
Death case is linear to confirmed cases i.e the more the confirmed cases, the more the death cases.
23rd of January 2021 was the day with highest infection rate.
For most states CCVI index is indirectly proportional to confirmed cases.
There’s a direct linear relationship between confirmed cases and population density. 
There’s an indirect relationship between confirmed cases and each of Age, Fragility, Health system, socio-Economic and Acute IHR
Effect of the pandemic was felt in the second quarter of 2020, when a lot of restriction was made. Q2 in 2020 has the lowest GDP since 2014.
According to the Manufacturing Association of Nigeria (MAN), manufacturers’ inventory of unsold goods rose to a record high of N402.4 billion as consumer spending fell.

## CONCLUSION
Covid-19 came as a shock and it’s effect can’t be overemphasized, on economy, manufacturing companies and consumers.
States with high population densities tend to have higher number of confirmed cases. This affirms to the significance of social distancing as a method of keeping safe to avoid contracting the virus.
Despite Borno state having a high fragility value and high Health system due to poor health facilities, the number of cases recorded was still quite low. Reason being that the population density is low.
GDP of Q2 of 2020 was most affected because of the restrictions made by government to reduce the spread of the virus.
There was a reduction in budget for every single state due to covid

## REFERENCES
Bloomberg report on economics
Nigeria economic alert (Pwc)
