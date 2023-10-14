# Bike Market Projection

## Table of Contents
- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Tools](#tools)
- [Data Anatomy](#data-anatomy)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Pivot Tables](#pivot-tables)
- [Recommendations](#recommendations)

### Project Overview

Bike market Data Analysis is my recent demo project completed using Microsoft Excel. The project was designed to test my skills in data analysis. The project was about using Data Analysis to predict regions where a company can expand their bike operations based on hypthotheical data available. The project is for a bike client who intends to spread sales in the three regions they operate in. The regions are North America, Europe and the Pacific. 

### Data source

### Tools
I only used Microsoft Excel

### Data Anatomy

The data consisted of over 1000 rows of 14 columns, including a unique ID, income, gender, region, bike ownership (denoted by either yes or no) and many more.

### Data Cleaning and Transformation

The data was downloaded, and on careful observation of the dataset, it was discovered that the data was not clean, and as such, that data had to be cleaned. Data cleaning began with checking for duplicate values, of which some records of duplicate values were found, which were more than 20. The duplicate values were removed using the removing duplicate function on the data pane of Excel. After that, a filter option was applied to each column to check if the data values were accurately written out or if there were no outdated values. 
#### Observation: 
It was discovered that there was inconsistency in the data. For example, the gender column had a mixture of "F," "M," "Male", and "Female." This had to be changed using the control + H button on the keyboard when the column was highlighted. The same was also applied to the Purchase bike column, which had a mixture of "Y," "N," "Yes," and "No ."The "F" and "M" were replaced with "Female" and "Male," respectively, while the "Y" and "N" were replaced with "Yes" and "No".
Finally, the age column was transformed into the age group column. This was done using the Excel formula "IF" statement. The "IF statement" was used to categorize the age group into adolescent (< 30), middle age (31-54) and old (55+)

### Pivot Tables

After data cleaning and transformation, ten pivot tables were created, followed by the graphical representation of the tables.
The Different pivot tables created included 
1. Commute Distance of Bike Owners
2. Average Income of Biker Owners by Gender\
3. Age Bracket of Bike Owners
4. Gender distribution by bike purchase
5. Average income of biker owners
6. Bike ownership by age group


- Commute Distance of Bike Owners

    ![Commute distance bike purchase](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/b6a9f577-8f3c-4eb4-90d7-d4c829d3fef4)

Generally, there is a correlation between Bike Ownership and commute distance. Usually, people with short commute distances tend to use bikes more. Thus, it was not surprising to see the line graph show that people on a 1-2-mile commute distance have more bikes than others with more commute distance. Individuals with more than 10 miles commute distance were very few for bike owners, with less than 50 compared to individuals without bikes in the same commute distance. This could mean that individuals with more commute are less likely to favour bike ownership.

### Average Income of Biker Owners by Gender
The average income of bike owners by gender revealed that males are more likely to use bikers than females, and the average income of bike owners for males is $59, 603 and for males without bikes is $56 250. While for females, 'the average income is $55 267 for bike owners and 53 450 for females without bikes. This suggests that higher earners have more disposable income for bikes.

![Average Income](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/b6049094-b094-4131-a5a8-581c5f419d8c)

### Age Bracket of Bike Owners
The Age bracket of bike owners showed that the middle age group of 31-54 had the most bikes while the adolescent group below 30 had the least.

![Age bracket](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/2229d0da-986d-4e82-bb21-2f501fa81427)

### Bike Purchase by Profession
The data gathered from the three regions showed that more skilled manual workers and professional workers bought bikes. The difference between

![profession](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/ee871a40-ea3b-494a-9c68-2eb95c059356)

### Bike Purchase by Region
Bike Purchases by region showed an interesting trend. The data showed more people bought Bikes in North America than in Europe and the Pacific. However, the population in Europe is more than that of North America. 

![Region](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/b476cf76-dcba-4f59-919a-5ad07e40a9f7)

Subsequently, further analysis discovered that the percentage of bike owners in North America is the lowest. The highest was the Pacific region. This meant fewer people within North America bought bikes, while more people in the Pacific bought bikes than those in Europe and North America.

![perceentage br region](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/c137bdd8-842c-46fd-8f39-cdbe555d6352)

This led me to drill down to the population, and I discovered that the Pacific region has more average income than North America.

![Income by region](https://github.com/TommyDatageek01/Bike-region-Analysis/assets/141424792/169de1e1-6498-496d-8e81-5556b7f8f1c2)

### Recommendations
From the data analytics and the dashboard created, we can suggest that the company should focus on the following;
1. Focus should be more on Urban areas of Europe, North America and the Pacific. This is because of the positive correlation between community distance and bike ownership. People commuting shorter distances are more likely to buy bikes. This would have more application in Urban areas with lots of traffic. This increased traffic has been found to affect urban dwellers. This explains the decrease in commute distance in Urban areas. With people seeking to commute for shorter distances, they certainly can expect bikes to have more applications to save time and cost. 
2.  Focus on maximizing the market share in the Pacific as more people marginally buy bikes than in Europe and America; from the data, about 58.91 percent of the population uses a bike, as against 41.09 percent that don't. This means an overwhelming percentage of the population uses bikes. The company should strongly consider expanding operations in the Pacific.
3.  The bike company should focus on the Pacific and Europe more for expansion. Although, as of 2022, Europe was leading in Bike Sales, there is a great resurgence of sales in North America coupled with the income; there could be a real chance that the market would open up WIth increased bike sales in North America. There is a plausible reason North American sales might outpace European sales. The company might position itself to cash in on the booming bike sales in North America, but it is worth noting that there might be stiff competition in all the regions, so more market research would have to be conducted to see how best to get  a sizable market share,











  
