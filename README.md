# fruit-database
Team name and members:

Yen Le, Princess Asenuga, and Jack Turner

Describing your dataset and what data it contains:

Imagine walking into a grocery store, trying to make smart, budget-friendly choices. You see fresh raspberries, canned cherries, and a carton of orange juice, but which one gives you the most edible fruit for your money? Without clear information on the price per usable amount of fruit, it’s easy to overpay for fruits that are low-yielding or expensive by serving size. Our Data was obtained from data.gov, a public U.S. government repository for open datasets. With 62 rows and 8 columns this dataset provides detailed pricing information for fruits in various forms (such as fresh, frozen, canned, dried, or juice) as sold in U.S. retail markets in 2022. Data set also includes retail prices and yield information that allows us to analyze fruit affordability.

The 2 questions the team generated and why they are interesting and important:

First question is “Is there any outlier in the data - a fruit that is disproportionately expensive or low yielding?” This is important for budget-conscious households. It also signals market anomalies, like premium pricing due to low availability, season changes, and import status. Second question is “How does the edible yield per dollar vary across different forms of fruit (canned, fresh, juice, frozen, and dried)?” This is important for producers/consumers to determine which products are most cost effective to make/buy!


The manipulations applied to the data set as part of the analysis:

The only manipulation we did was for the second question where we created another variable called the Edible Volume by Dollar. This was calculated by dividing the yield by the retail price of the fruit.

Analysis and Results:

Question 1: Is there any outlier in the data - a fruit that is disproportionately expensive or low yielding?

Analysis: In Tableau, “Form” was placed in columns and “Cup Equivalent Price” was placed in rows to organize the fruits by category and measure their price distribution. Boxplots make it easy to spot skewness and variability across the different fruit forms. Unlike bar charts or line graphs, a box plot compactly summarizes large amounts of data, making patterns and price variability easily visible.

Results: Canned cherries are a strong outlier at $3.50 per cup. Fresh raspberries and blackberries are notable outliers in the fresh category, priced at over $2.50 per cup. Outliers like canned cherries and fresh raspberries indicate products with a higher risk of price instability, which is important for both budget planning and inventory management. Identifying high price outliers helps consumers avoid cost spikes and lets businesses optimize their sourcing strategies. Stable fruit forms such as juices and dried fruits offer a more predictable pricing, making them better for consistent budgeting.

Question 2: How does the edible yield per dollar vary across different forms of fruit (canned, fresh, juice, frozen, and dried)?

Analysis: Bar graph clearly compares values across categories, & highlights dramatic differences through color coding and length of each bar (form was added into color filter). Bar graph maintains proportional accuracy more effectively than tables, pie charts, etc. Grouping rows by form, rather than fruit, provides a cleaner visualization of value than listing every individual fruit in our dataset. 

Results: Juice has the highest average edible yield per dollar, making it the most cost-effective fruit form overall. Fresh fruit ranks closely behind juice, showing strong average value despite price variability across individual fruits. Consumers can use this data to choose juice or fresh fruits when looking for the best value per dollar spent. Producers and retailers may emphasize juice products in marketing as cost-efficient and high-yield. Meal planners, schools, and institutions might prioritize higher-yield forms to stretch budgets. Dried fruit brands could reframe their products as premium or snack-focused, rather than bulk nutritional value. This average-based analysis supports strategic product development, pricing, and purchasing decisions across the supply chain.


Tableau Package Workbook:


<img width="663" alt="Screenshot 2025-05-01 at 7 48 42 PM" src="https://github.com/user-attachments/assets/d18ac2bd-dbc5-407e-968b-028a910a97ca" />


<img width="408" alt="Screenshot 2025-05-01 at 7 48 51 PM" src="https://github.com/user-attachments/assets/847ba90a-0bfa-4b7e-8889-832240bf6e8b" />
