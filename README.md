# shopping-behavior

Overview: Exploratory Analysis of American Shopping Behavior for FlashFash

This project aims to analyze the shopping behavior of American consumers utilizing the raw shopping data provided by the company FlashFash. FlashFash is an online shopping company with the interest in understanding and tapping into the American consumer landscape. 

Utilizing the sample dataset, the goal is to derive descriptive statistics and visualizations to gain insight into consumer preferences. The key aim is to understand the seasonality of shoppers, identify the demographics making the most purchases and strategize market outreach to maximize sales. 

The questions focused on addressing include identifying popular colors by season, popular clothing items by season, effect of promo-codes on purchase amount, and user review trends. By addressing these questions, the aim is to be able to optimize inventory management based on consumer preferences, improve marketing campaigns, and enhance promotional strategies. 

## Observations 

Workflow: 

The approach to this project included the exploring of the raw shopping dataset that we were provided. This step included the use of Seaborn and Matplotlib to create visualizations of our data. From there the data was then transformed, removing columns that were irrelevant or that contained too many missing values, resulting in a clean dataset. From there, using pandas methods helped further explore our clean dataset to conduct more in depth data analysis.  

Observations: 

Shopper Distribution by State: 
- California stands out as the state with the highest number of shoppers, as evidenced by our bar plot. On the other hand, Hawaii represents the state with the lowest number of shoppers.

Seasonal Purchase Trends: 
- The data indicates that Winter sees the largest volume of purchases, as highlighted by our bar plot analysis.

Preferred Payment Method: 
- Credit card appear as the most popular form of payment among US customers, while cash is the least favored option.

Age Distribution: 
- The analysis of the Age column reveals a right-skewed distribution. This suggests that the typical US shopper falls within a younger age bracket, typically ranging from 20 to 40 years old.

Purchase Amount Distribution: 
- The Purchase Amount (USD) column indicates a normal distribution. Few outliers were observed in our boxplots, indicating a lack of skewness in the data.

T-Test Conclusion: 
- The calculated t-statistic (statistic=93.2464714350831) indicates a significant difference between the two groups. The p-value (pvalue=0.0) from our t-test comparing promo-code and non-promo-code users leads us to reject the null hypothesis. This suggests a significant difference in the dollar amount spent by users who utilize promo codes compared to those who do not.

Interpretation: 

The observations offer valuable insights into consumer behavior and preferences, that further inform business decisions. Understanding shopper distribution by state guides resource allocation and marketing strategies. Knowledge of preferred payment optimizes checkout processes and logistics. Age distribution informs product development and marketing tactics. Analysis of purchase amount distribution aids pricing strategies and promotional campaigns. Additionally, the outcome of the t-test on promo-code usage provides insights into the effectiveness of marketing efforts. These insights inform businesses to enhance customer satisfaction, drive sales, and optimize operational efficiency.