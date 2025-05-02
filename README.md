# MIST4610-Project2-Group3

## Team Name: 
71552 Group 3

## Team Members:
1. Jack Turner [@JackTurner123](https://github.com/JackTurner123/fruit-database.git)
2. Yen Le [@YenLeMIST](https://github.com/YenLeMIST/FruitPrices)
3. Pariprita Mallavarapu [@paripritam](https://github.com/paripritam/fruit-database/blob/main/README.md)
4. Princess Asenuga [@] ()

## Dataset Overview

Imagine walking into a grocery store, trying to make smart, budget-friendly choices. You see fresh raspberries, canned cherries, and a carton of orange juice, but which one gives you the most edible fruit for your money? Without clear information on the price per usable amount of fruit, it’s easy to overpay for fruits that are low-yielding or expensive by serving size. Our Data was obtained from data.gov, a public U.S. government repository for open datasets. With 62 rows and 8 columns this dataset provides detailed pricing information for fruits in various forms (such as fresh, frozen, canned, dried, or juice) as sold in U.S. retail markets in 2022. Data set also includes retail prices and yield information that allows us to analyze fruit affordability.

## Question 1
Is there any outlier in the data - a fruit that is disproportionately expensive or low yielding?

<img width="663" alt="Screenshot 2025-05-01 at 7 48 42 PM" src="https://github.com/user-attachments/assets/22a225fc-7a0a-4e15-9b2b-ad2300807e26" />


In Tableau, “Form” was placed in columns and “Cup Equivalent Price” was placed in rows to organize the fruits by category and measure their price distribution. Boxplots make it easy to spot skewness and variability across the different fruit forms.

This is important for budget-conscious households. It also signals market anomalies, like premium pricing due to low availability, season changes, and import status. Second question is “How does the edible yield per dollar vary across different forms of fruit (canned, fresh, juice, frozen, and dried)?” This is important for producers/consumers to determine which products are most cost effective to make/buy!

This is interesting because it helps identify fruits that don't follow the typical price-to-yield trend. This matters for budget-conscious shoppers trying to get the most value, and it also reveals potential market factors like scarcity, seasonality, or import costs that affect pricing. Spotting outliers can lead to smarter consumer choices and better business decisions for retailers and suppliers.

## Question 2
How does the edible yield per dollar vary across different forms of fruit (canned, fresh, juice, frozen, and dried)?

<img width="408" alt="Screenshot 2025-05-01 at 7 48 51 PM" src="https://github.com/user-attachments/assets/c0f34cbe-2d53-45d6-a638-0d07c5442771" />


Bar graph clearly compares values across categories, & highlights dramatic differences through color coding and length of each bar (form was added into color filter). Bar graph maintains proportional accuracy more effectively than tables, pie charts, etc. Grouping rows by form, rather than fruit, provides a cleaner visualization of value than listing every individual fruit in our dataset.  

This question helps identify which form of fruit offers the best value, which is useful for both budget-conscious consumers and producers looking to price competitively. Understanding edible yield per dollar can guide smart purchasing and production choices, especially when cost efficiency matters. It also supports informed decisions in settings like schools, meal prep services, or food banks.

It’s interesting because the same fruit can have very different value depending on how it's processed—fresh apples vs. apple juice, for example. This comparison can reveal surprising trends about food pricing and processing efficiency. It also opens up questions about convenience, shelf life, and consumer preferences.


## Manipulations
The only manipulation we did was for the second question where we created another variable called the Edible Volume by Dollar. This was calculated by dividing the yield by the retail price of the fruit.


## Analysis and Results
In terms of question one, we can see that mortality trends for both diseases are declining, reflecting the impact of public health interventions (e.g. vaccines and awareness campaigns). Mortality rates are higher in densely populated states and lower in states with fewer people, emphasizing regional differences. California, Florida, and Texas had the highest mortality rates for both causes and this could be attributed to their population size. According to the Population Reference Bureau, in 2020, California, Florida, and Texas have the highest populations for those over the age of 65, which can explain why these trends appear in the visualizations. COVID-19 is a novel virus, resulting in much higher mortality rates across all states. Influenza is a seasonal diseases with established vaccines and treatments, leading to lower or zero mortality in some states.

For our second question, natural causes maintain the leading causes of mortality throughout 2020-2023. COVID-19 spikes in 2020 and 2021, but tapers off in 2022 and 2023. Regardless, the deaths from natural causes, heart diseases, and malignant neoplasms were still higher than deaths from COVID-19. Diseases of the heart and malignant neoplasms (cancerous tumors) showed relatively consistent patterns over the course of the four years yet continued to be significant contributors to overall mortality. For each cause of death, there was a downward trend from 2023-2024, which could indicate better healthcare and a higher quality of overall health. The gap between COVID-19 deaths and other causes of death began to widen from the end of 2021 to 2023, which again could show the progress made on handling the pandemic within the country. In terms of the Southeast region itself, the trends within the region reflected the trends within the United States very similarly. The number of deaths in the Southeast made up around 10% of the deaths in the United States. 

## Sources
(https://catalog.data.gov/dataset)
