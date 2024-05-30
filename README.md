# Instacart-Grocery-Basket-Analysis

## BUSINESS CASE

Instacart, an online grocery store that operates through an app. Instacart already has very good sales, but they want to uncover more information about their sales patterns. The goal is to perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.

## DATA SOURCE

- The following data sets are open-source data sets from Instacart. Instacart is a real company that’s made their data available online. However, the "customer" data set and the "prices" columnn have been fabricated for the purpose of CareerFoundry Data Analysis course project.
- "The Instacart Online Grocery Shopping Dataset 2017", Accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle on February 2024.

## METHODOLOGY

- Data Consistency Checks
- Data Wrangling & Subsetting
- Merging different dataframes
- Creating new columns using if-statements, user-defined functions, the loc() function, and for-loops
- Grouping and aggregating data
- Data visualization with Python
- Reporting

## TECH STACK
- Language: Python
- Libraries: Pandas, Numpy, Matplotlib, Seaborn, Scipy

## KEY QUESTIONS & INSIGHTS

**1. What are the busiest days of the week and hours of the day in terms of orders?**

<img width="397" alt="Screenshot 2024-05-30 at 16 42 07" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/07f93984-aee6-428b-a6b5-189979591882">
<img width="416" alt="Screenshot 2024-05-30 at 16 43 30" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/6b2ff8ec-2415-459a-92a2-329d25d53dc8">

- Busiest days of the week are Saturdays (0) and Sundays (1) where most of the orders take place.
- Slowest days are Tuedays (3) and Wednesdays (4) where the least amount of orders take place.
- Mondays(2), Thursdays(5) and Fridays(6) are regular days in terms of orders.
- The busiest time of day is between 11:00 and 16:00 with most sales 

**2. Are there are particular times of the day when people spend the most money?**

<img width="531" alt="Screenshot 2024-05-30 at 16 44 34" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/ee8fc5f6-d377-4661-8069-d658e12c56ba">

- Analysis suggests that the early morning hours around 3 am to 4 am has the highest price for orders, following a sharp decline around 5am. There is a gradual increase until 9am in which followed by routine orders during the day until around 10pm.

**3. What could be a simpler price range groupings for Instacart's big inventory of products with different price tags?**

**4. Are there certain types of products that are more popular than others? Which departments have the highest frequency of product orders?**

<img width="668" alt="Screenshot 2024-05-30 at 16 46 50" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/2c30c4ba-1670-49fd-8c22-d758d003b130">

- Top 10 products for ordering includes items almost exclusively from the produce department (include fruits, vegetables, and other fresh items)

**5. What’s the distribution among users in regards to their brand loyalty?**

<img width="468" alt="Screenshot 2024-05-30 at 16 49 22" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/76af107d-2d7f-409e-9e5b-50bf28100f9e">

- 52% of customers are classified as regular, making purchases every 10 to 20 days, making up the majority of the customer base while 31.7% are classified as loyal, returning within 10 days. 

**6. Are there differences in ordering habits based on a customer’s loyalty status?**

<img width="1000" alt="Screenshot 2024-05-30 at 16 50 25" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/603afc19-8076-4f4f-972c-07dee380bd41">

- There is not a significant difference in department sales based on customer loyalty. However, there are some differences in number of orders by day of the week in each loyalty groups.
- Although each loyalty group shops mainly on Saturdays and Sundays , loyal customers shop the most on Sundays rather than Saturdays. Similarly, the least busy days are Wednesday and Tuesdays in general, while the least busy days are Tuesdays rather than Wednesdays for loyal customers.
- There is also noticible difference in spending habits between high and low spenders. Low spenders shop more often than high spenders.

**7. Are there differences in ordering habits based on a customer’s region?**

<img width="841" alt="Screenshot 2024-05-30 at 16 51 55" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/3afb3f20-e00a-4b0e-ab9e-eb4220902342">

- The South has a highest number of customers so it has high sales than other regions 
- Consistently across all regions, there is a balanced distribution between high and low spenders.  

**8. Is there a connection between age and family status in terms of ordering habits?**

<img width="1399" alt="Screenshot 2024-05-30 at 16 53 01" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/b5bac6ce-321d-449f-a281-5c477dc67583">

- Majority of customers are married so targeting this groups would be crucial. 
- Analysis shows slight differences in spending across different age and marital status categories. Individuals living with parents and siblings usually spend the least, while singles shows higher spending habits.

**9. What different classifications does the demographic information suggest?**

<img width="527" alt="Screenshot 2024-05-30 at 16 54 19" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/68bda892-30c9-4054-b987-050bded18aa2">

- The demographic information shows a positive correlation between age and income. As age increases, income will increase too.
- What is significant here is that there a considirable increase in income of the middle age group. 
  
**10. What differences exist in ordering habits of different customer profiles?**

<img width="956" alt="Screenshot 2024-05-30 at 16 55 32" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/65ab3062-be02-4fe0-83a7-a0a51f1e9354">

<img width="836" alt="Screenshot 2024-05-30 at 16 56 22" src="https://github.com/slcnyrnc/Instacart-Grocery-Basket-Analysis/assets/167687192/04d7ec4e-146f-496d-8281-3fcbeea405ec">

- The higher the income, the more the customer will spend as expected.
- Middle class and married groups generate the most sales
- Most popular departments for each group showed very little differences. Produce remains the most popular.

## RECOMMENDATIONS

- In order to increase sales during non busy hours, consider scheduling ads during non busy hours (11:00 to 16:00) on the busiest and regular days.
- Avoid running ads at night when most customers are asleep.
- Focus on advertising on Saturdays and Sundays as they are the busiest days of the week in terms of orders.
- Consider running more ads from Monday to Friday to increase number of sales during weekdays.
- 3am to 4am could be used to promote a broad range of products to attract customers who are more active early in the day.        
- 5am to 9am sees a gradual increase, indicating that people are starting their day and possibly commuting to work. This time could be used to promote products that cater to busy professionals, commuters, or families getting ready for the day. 
- 9am to 10pm routine orders are observed, suggesting a variety of products that cater to everyday needs or leisure activities.
- Consider prioritising the produce department as they contribute to the largest sales.
- There should be a loyalty program to incentivise loyal customers to remain loyal and also various discounts and offers to motivate rest of the customers to make orders to reach the loyal status.
- New customers should receive discounts after their first purchase to encourage them to continue shopping. 
- Targeting more middle age groups that are not using the platform would be potential for more sales as they have the necessary income to shop on a regular basis.




