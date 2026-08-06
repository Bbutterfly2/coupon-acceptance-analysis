Coupon Acceptance Analysis 

Project Overview 

This project explores customer behavior using the UCI Coupon Recommendation dataset. The goal is to identify factors that influence whether a driver accepts a coupon while driving. 

The analysis was completed using Python in Jupyter Notebook with pandas, Matplotlib, and Seaborn. 

--- 

Dataset 

The dataset contains information about: 

- Driver demographics 

- Destination 

- Weather 

- Time of day 

- Passenger type 

- Coupon type 

- Whether the coupon was accepted 

--- 

Objectives 

The analysis focuses on: 

- Cleaning missing data 

- Exploring coupon acceptance rates 

- Investigating Bar coupon acceptance 

- Performing an independent investigation on Restaurant coupons 

- Drawing conclusions from the results 

--- 

Tools Used 

- Python 

- pandas 

- NumPy 

- Matplotlib 

- Seaborn 

- Jupyter Notebook 

--- 

Key Findings 

Bar Coupon Analysis

Based on these observations, I hypothesize that drivers who regularly visit bars are much more likely to accept bar coupons than those who don't really visit bars. Drivers who visited bars more than three times a month had an acceptance rate of 73%, compared to only 29% for those who visited bars fewer than three times per month. 
Drivers who visited bars more than once a month and were under the age of 30 had the highest acceptance rate at 81%, suggesting that younger people who go to bars are the most likely to use the bar coupons. Drivers who went to bars, were not traveling with children, and were not widowed also had a high acceptance rate at 73%.
However, drivers who frequently visited cheaper restaurants and had an income below $50,000 had a lower acceptance rate of about 45%. In conclusion, these results suggest that a person's bar going behavior is the strongest indicator to whether they would accept a bar coupon or not. Age and some social constructs also seem to
influence acceptance behavior.

Restaurant Coupon Investigation

This explored the characteristics of drivers who accepted Restaurant coupons. The analysis compared coupon acceptance across several  characteristics : income, destination, time of day, age, and passenger type. The visualizations showed that acceptance rates varied among these groups. Showing that customer demographics and the
context of the trip influences a person's acceptance of a restaurant coupon. I would say restaurant coupons appear to be more successful when offered to drivers whose travel plans and personal characteristics align with dining opportunities. If it is conviennt to the driver, it will have a higher chance of being used. These show
that to get more people to use coupons they should target promotions based on demographics and driving data. 


Author 

Anushri Selva 
