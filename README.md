# MIST4610-Project2-Group3

## Team Name: 
71552 Group 3

## Team Members:
1. Jack Turner [@JackTurner123](https://github.com/JackTurner123/fruit-database.git)
2. Yen Le [@YenLeMIST](https://github.com/YenLeMIST/FruitPrices)
3. Pariprita Mallavarapu [@paripritam](https://github.com/paripritam/fruit-database/blob/main/README.md)
4. Princess Asenuga [@Princessase](https://github.com/Princessase/Fruit)

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
In terms of question one, canned cherries are a strong outlier at $3.50 per cup. Fresh raspberries and blackberries are notable outliers in the fresh category, priced at over $2.50 per cup. Juice and dried fruits show low price variability and minimal outliers, making them more predictable for both inventory planning & budgeting. Fresh watermelon is a low-cost outlier, by far the best value option for fresh fruit Outliers like canned cherries and fresh raspberries indicate products with a higher risk of price instability, which is important for both budget planning and inventory management. Identifying high price outliers helps consumers avoid cost spikes and lets businesses optimize their sourcing strategies. Stable fruit forms such as juices and dried fruits offer a more predictable pricing, making them better for consistent budgeting.


For our second question, Juice has the highest average edible yield per dollar, making it the most cost-effective fruit form overall. Fresh fruit ranks closely behind juice, showing strong average value despite price variability across individual fruits. Canned fruit provides solid mid-range cost-efficiency on average. Frozen fruit has a lower average yield per dollar, but may still appeal due to convenience and shelf life. Dried fruit offers the least average yield per dollar, suggesting lower cost-efficiency in typical purchases. Consumers can use this data to choose juice or fresh fruits when looking for the best value per dollar spent. Producers and retailers may emphasize juice products in marketing as cost-efficient and high-yield. Meal planners, schools, and institutions might prioritize higher-yield forms to stretch budgets. Dried fruit brands could reframe their products as premium or snack-focused, rather than bulk nutritional value. This average-based analysis supports strategic product development, pricing, and purchasing decisions across the supply chain.

## Sources
(https://catalog.data.gov/dataset)
