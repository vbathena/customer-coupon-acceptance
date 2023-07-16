# Customer In-Vehicle Coupon Acceptance Project
> This repository contains the Customer In-Vehicle Coupon Acceptance dataset, which provides information about different driving scenarios, passenger attributes, contextual attributes and coupon attributes. The dataset aims to explore the characteristics of passengers who accept various types of coupons and provide insights for coupon acceptance recommendation.

## General Information
- Dataset analysis work completed in Jupyter Notebook. Link here [Jupyter Notebook](customer_coupon_acceptance.ipynb)
- Dataset in *data* folder
- Images in *images* folder

## Summary of Findings
Based on the data provided, the following key findings have been summarized:

1. Dataset Overview:
   
   - The dataset contains 18 categorical and 8 numerical features.
   - There are 74 duplicate rows in the dataset.

2. Missing Values:

   - The "Car" feature has 99% missing values, while other features have 1% missing values.
   - Occupation feature has a large number of unique values.

3. Correlation:

   - "direction_same" and "direction_opp" features are perfectly correlated.
   - "tocoupon_geq5min" does not correlate with any other feature.

4. Balance:

   - The dataset is partially balanced, with a coupon acceptance rate of 57% and coupon rejection rate of 43%.

5. Coupon Types:

   - The greatest number of coupons offered are for Coffee House.
   - Coupons for Carry out & Take away and Cheap Restaurants have the highest acceptance rates.
   - Coupons for Bars and Expensive Restaurants have low acceptance rates.

6. Temperature Influence:

   - Most drivers prefer to go out when the temperature is high and have a high coupon acceptance rate.
   - When the temperature is low, the coupon acceptance rate is low.

7. Bar Coupons:
   
   - 41% of the drivers accepted bar coupons.
   - Drivers who go to bars more often may be more likely to accept the coupons.
   - Drivers who go to a bar more than once a month and are over the age of 25 have a slightly higher acceptance rate.

8. Coffee House Coupons:
       
   - The number of drivers accepting Coffee House coupons is almost the same as the number of drivers rejecting them.
   - The coupons were not effective in encouraging passengers to purchase coffee at Coffee House.
   - Male and female drivers have similar acceptance rates for Coffee House coupons.
   - Drivers who go to Coffee House more than once a month, male, and over the age of 30 are more likely to accept the coupons.

9. Additional Thoughts on Driver Preferences:
   
   - Younger drivers, single drivers, drivers with higher income, and drivers with occupations other than farming, fishing, or forgery may be more likely to accept coupons and try new things.
   - Rainy weather and warm weather may have a slight influence on acceptance rates for coffee house coupons.
   - Drivers with higher incomes and education levels are more likely to accept coupons and try new coffee houses.

These findings provide some insights into driver preferences for different types of coupons and factors that may influence their acceptance rates.

## Technologies Used
- Seaborn
- Pandas
- Numpy


## Future Work
Future work could focus on expanding the dataset to include more drivers and coupons. Additionally, explore other factors that influence the acceptance of coupons, such as the time of day, the weather, and the driver's mood.


## Conclusion
Overall, the findings suggest that coupon acceptance is influenced by a number of factors, including the type of coupon, the driver's demographics, and the weather. Based on these findings, businesses can use the insights from this dataset to improve their coupon campaigns in a number of ways. For example, businesses can target their coupon offers to specific times of day, days of the week, or weather conditions. Businesses can also use the data to identify drivers who are more likely to be receptive to coupons and target those drivers with specific offers. More research is needed to better understand these relationships and to develop more effective coupon recommendation strategies for businesses to improve their coupon campaigns and increase the likelihood of acceptance.


## Contact
Created by [@vijayin26](https://www.linkedin.com/in/vijayabhaskarreddybathena/) - feel free to contact me!