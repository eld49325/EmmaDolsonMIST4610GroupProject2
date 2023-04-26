# EmmaDolson_MIST4610GroupProject2

# 21479_8 Members
- [Emma Dolson](https://github.com/eld49325/EmmaDolson_MIST4610GroupProject2)
- [Hannah Kelly]()
- [Shir Kochi]()
- [Donovan Vanderpool]()
- [Kaden Williams]()

# Dataset
This data was pulled from the US Energy Administration and joined together for an easier analysis. It is a collection of major factors that play into C02 emissions, from the Production and Consumption of each type of major energy source for each country to its pollution rating each year. It also includes each countries GDP, Population, Energy intensity per capita (person), and Energy intensity per GDP (per person GDP). All the data spans all the way from the 1980's through 2019.

Feature Descriptions:
- Country: Country in question
- Energy_type: Type of energy source
- Year: Year the data was recorded
- Energy_consumption: Amount of Consumption for the specific energy source, measured (quad Btu = 10¹⁵ British thermal unit)
- Energy_production: Amount of Production for the specific energy source, measured (quad Btu)
- GDP: Countries GDP at purchasing power parities, measured (Billion 2015$ PPP)
- Population: Population of specific Country, measured (Mperson)
- Energy_intensity_per_capita: Energy intensity is a measure of the energy inefficiency of an economy (Calculated as units of energy per unit of capita, measured as MMBtu/person)
- Energy_intensity_by_GDP: Energy intensity is a measure of the energy inefficiency of an economy. It is calculated as units of energy per unit of GDP, measred (1000 Btu/2015$ GDP PPP)
- CO2_emission: The amount of C02 emitted, measured (MMtonnes CO2)

# Question 1
People have employed several approaches to curbing CO2 emissions, ranging from policy changes and regulations to technological advancements and behavioral changes. In 2019, Prince Harry and Meghan Markle announced they would limit their family size to two children, citing environmental reasons. This led people to question if family planning is an effective solution to reducing CO2 emissions. Population growth has been linked to increased CO2 emisssions as  increased demand for resources, including energy, food, and transportation, which all contribute to greenhouse gas emissions. However, it is important to note that the correlation between population and CO2 emissions is not straightforward, as other factors such as economic development contribute to CO2 emissions. Economic growth is often accompanied by increased energy demand for transportation, manufacturing, construction, and other sectors, resulting in increased CO2 emissions. This prompted us to ask the question:

Is there a stronger correlation between CO2 emissions and GDP or CO2 emissions and population? 

# Question 1 Analysis and Results
![Q1Dashboard](https://user-images.githubusercontent.com/128401988/234453303-e20e7c0e-2ff5-451b-8cb2-669f63dd2d14.png)

For the top two graphs, we examined the top five countries with the highest CO2 emissions overall (China, US, India, Russia, and Japan). In doing so, the data points are more visible and eliminate less significant countries that could possibly skew the data. 

Looking at the visualization between Energy Intensity by GDP vs Energy Intensity per capita, we observed both measures following similar trends year to year with the exception of China. After 2013, China's Energy Intensity by GDP decreases while its Energy Intensity per capita continues to increase. Upon further research, we found this was a result of China's energy restructuring to increase production from its statewide power generators and reduce its reliance on coal. With the other countries' Energy Intensity by GDP and Energy Intensity per capita following parallel trends, the graph reaffirms our hypothesis that GDP and population are contributing factors towards CO2 emissions.

The visualization between Population and GDP shows us there may not be a strong correlation between population and GDP themselves. Looking at the United States, it has the highest GDP in the world yet it has a significantly smaller population compared to China and India. From this graph, we can assume these disparaties will lead to a difference in the correlation between CO2 emissions and population and the correlation between CO2 emissions and GDP.

In the bottom two graphs, we ran a linear regression on the correlation between CO2 emissions and population and the correlation between CO2 emissions and GDP. For both population and GDP, the p-values were less than 0.0001  and reaffirmed our hypothesis that they were statistically significant in contributing to CO2 emissions. The R-squared for CO2 emissions and GDP was 0.8693, which was higher than the R-squared between CO2 emissions and population of 0.6276. This answers our question as the CO2 emissions and GDP has a stronger correlation than the correlation between CO2 emissions and population. The implication of our findings suggests economic policies may have a stronger effect on reducing CO2 emissions than population control.

# Question 2 
The Paris Climate Agreement is a global treaty that was adopted in 2015 by 196 countries with the goal of limiting global warming to well below 2°C above pre-industrial levels and pursuing efforts to limit it to 1.5°C. The agreement requires each country to set its own targets for reducing greenhouse gas emissions and regularly report on their progress. While many countries have made efforts to reduce their greenhouse gas emissions, some countries' commitments fall short of the global warming goal and other countries have withdrawn from the agreement or not yet ratified it. In 2017, the U.S. was one country that withdrew from the Paris Climate Agreement only to rejoin it in five years later. With the controversy surrounding its' validity, we used our datset to answer the question:

How effective has the Paris Climate Agreement been in reducing CO2 emissions?

# Question 2 Analysis and Results


# Manipulations
No manipulations or calculations were performed on the data set. For relevance, we filtered our time period to the decade of 2009-2019 to reduce outliers and exclude countries that no longer exist (e.g. USSR, West and East Germany).
