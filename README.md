# Customer Coupon Acceptance Project
> This repository contains the Customer Coupon Acceptance dataset, which provides information about different driving scenarios, passenger attributes, contextual attributes and coupon attributes. The dataset aims to explore the characteristics of passengers who accept various types of coupons and provide insights for coupon acceptance recommendation.

## General Information
- Dataset analysis work completed in Jupyter Notebook. Link here ([customer_coupon_acceptance.ipynb](https://github.com/vbathena/customer-coupon-acceptance/blob/main/customer_coupon_acceptance.ipynb))
- Dataset in *data* folder
- Images in *images* folder

## Summary of Findings
Based on the data provided, the following key findings have been summarized:

1. Dataset Overview:
   
   - The dataset contains 18 categorical and 8 numerical features.
   - There are 74 duplicate entries that should be addressed.

2. Missing Values:

   - The "car" feature is missing 99% of the values and should be dropped.
   - Other features have approximately 1% missing values, which can be filled.
   - Occupation feature has a large number of unique values.

3. Unique Values:

   - The "occupation" feature contains too many unique values, which may require further analysis or handling.
   
4. Correlation:

   - "direction_same" and "direction_opp" features are perfectly correlated, indicating redundancy. One of them can be removed.
   - "tocoupon_geq5min" does not show significant correlation with other features and can be dropped or assigned a constant value.

5. Balance:

   - The dataset is partially balanced, with a coupon acceptance rate of 57% and rejection rate of 43%.

6. Coupon Types:

   - Coffee House offers the highest number of coupons.
   - Carry out & Take away and Cheap Restaurants coupons have the highest acceptance rates.
   - Bars and Expensive Restaurants coupons have low acceptance rates.

7. Temperature Influence:

   - Most drivers prefer to go out when the temperature is high and have a high coupon acceptance rate.
   - When the temperature is low, the coupon acceptance rate is low.

8. Bar Coupons:
   
   - 41% of drivers accepted bar coupons, while the number of rejections was higher.
   - Drivers who go to bars more often are more likely to accept the coupons.
   - Drivers who go to a bar more than once a month and are over the age of 25 have a slightly higher acceptance rate.
   - Occupation, non-kid passengers, and age also seem to influence the acceptance of bar coupons.

9. Coffee House Coupons:
       
   - 49.9% of drivers accept Coffee House coupons.
   - The coupons were not effective in encouraging passengers to purchase coffee at Coffee House.
   - Male and female drivers have similar acceptance rates for Coffee House coupons.
   - Male drivers who go to a coffee house more than once a month and are over the age of 30 are more likely to accept Coffee House coupons.
   - Rainy weather and going to a coffee house in the morning increase the likelihood of accepting the coupons.
   - Going to a coffee house with friends, having a bachelor's degree, and a higher income also make drivers more likely to accept the coupons.

10. Additional Thoughts on Driver Preferences:
   
   - Younger drivers, single drivers, drivers with higher income, and drivers with occupations other than farming, fishing, or forgery may be more likely to accept coupons and try new things.
   - Rainy weather and warm weather may have a slight influence on acceptance rates for coffee house coupons.
   - Drivers with higher incomes and education levels are more likely to accept coupons and try new coffee houses.

These findings provide insights into the acceptance rates of different coupon types based on various factors such as bar visits, coffee house visits, weather conditions, and driver characteristics.

## Technologies Used
- Seaborn
- Pandas
- Numpy

## Future Work
Future work could focus on expanding the dataset to include more drivers and coupons. Additionally, explore other factors that influence the acceptance of coupons, such as the time of day, the weather, and the driver's preferences. 

## Conclusion
Overall, the findings suggest that coupon acceptance is influenced by a number of factors, including the type of coupon, the driver's demographics, and the weather. Based on these findings, businesses can use the insights from this dataset to improve their coupon campaigns in a number of ways. For example, businesses can target their coupon offers to specific times of day, days of the week, or weather conditions. Businesses can also use the data to identify drivers who are more likely to be receptive to coupons and target those drivers with specific offers. More research is needed to better understand these relationships and to develop more effective coupon recommendation strategies for businesses to improve their coupon campaigns and increase the likelihood of acceptance.


## Contact
Created by [@vbathena](https://www.linkedin.com/in/vijayabhaskarreddybathena/) - feel free to contact me!
