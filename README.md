# Will a Customer Accept the Coupon?

This data study examines whether a driver will accept the coupon presented to them in different driving scenarios.

## Description
From a business perspective, the goal of this data task is to analyze different factors that affect the coupon acceptance rate, the dataset provides insights into whether a driver accepts the coupon once its delivered to them and the factors that influence the likelihood of the acceptance of different coupons such as Bar, CoffeHouse, Carry out & Take away, Restaurant with average expense less than $20,  Restaurant with average expense between $20-$50.

## Getting Started :
To get started with this project, we need to have the following dependecies :
* Python 3.6+
* Jupyter Notebook
* Coupon Dataset
* Python libraries such as pandas,matplotlib, seaborn.

## Analysis - Coupon Acceptance for Bar and Carry out & Take away

#### Bar Coupon Acceptance 

###### Drivers who accepted bar coupon :

* The proportion of total observations that accepted the Bar coupon is 41.2%. This indicates a significant portion of the drivers accepted the coupon.
* Drivers who go to a bar less than 3 times have an acceptance rate of ~32.8%, and the drivers who visit more than 3 times have an acceptance rate of ~67.2%, so its clear that drivers who visit more frequently have higher chance of accepting the coupon.
* Drivers who go to a bar more than once a month and are above the age of 25 have the highest acceptance rate of 67.2%, indicating that regular bar visitors above age of 25 are more likely to accept the offer.
* Drivers who go to bar more than once a month have acceptance rate of 43.3% and drivers with passengers that were not a kid have acceptance rate of 30.7% and drivers with occupations other than farming, fishing, or forestry have 26% acceptance rate, so indicating frequent bar visitors and drivers with passengers and no kid have higher rate to accept the coupon.


###### Drivers who did not accept bar coupon :

* Drivers who go to a bar less than 3 times have less acceptance rate compared to drivers who visit more than times.
* Drivers below the age of 25 and who doesnt visit bar frequently have a lower acceptance rate of 32.8%, so this group appears to be less interested in accepting the coupon.
* Drivers who have no kids, are not widowed, and drivers that go to a bar more than once a month and are over the age of 30 have acceptance rates ranging between 37.8% to 38.1%, these groups demonstrate a moderate likelihood of accepting the coupon, while drivers that go to cheap restaurants more than 4 times a month with income is less than 50K have less acceptance rate of 24.1% compared to other groups.

#### Carry out & Take away

######  Carry Away coupon acceptance criteria :
* The proportion of drivers accepted Carry out & Take away coupons is 73.6%, this indicates significant portion of the drivers accepted the CarrayAway coupons.
* Most of the drivers irrespective of their CarrayAway frequency they accepted the coupons.
* Drivers with occupation in 'Building & Grounds Cleaning & Maintenance', 'Construction & Extraction', 'Protective Service' and 'Healthcare Practitioners & Technical' sectors tend to visit CarrayAway more than others.
Based on the time, significant drivers carryAway at 2PM, 6PM and 10PM compared to morning hours.

######  Carry Away coupon non-acceptance criteria :

* Weather does not significantly affect the acceptance rate of Carry out & Take away
* Divers are less likely to CarrayAway in the morning hours
* Drivers who visit CoffeHouse more than 4 times tend to accept less CarrayAway coupons than others.


## Next steps and recommendations

* `Time Based Promotions:` Leverage observed preferences for time based promotions, provide attractive discounts for the morning hours as they appeared to be accepted less compared to other time of the day.
* `Segmented Marketing:` Use customer data to target specific groups with relevant coupons, target drivers who visit coffeHouse and cheap restuarants and offer them attractive discounts, also offer special incentives to frequent visitors and first-time buyers.
* `Bundle Deals:` Consider offering bundle deals, such as "buy one, get one half-off" or "meal deals" where drivers can save money when they order multiple items.
* `Monitor and Analyze Results:` Keep track of which coupons are performing well and which aren't. Use this data to refine your coupon strategy over time.
* `Feedback and Surveys:` Collect feedback from drivers on their coupon preferences. This can help tailor coupon offerings to better match their preferences.

Overall, it is crucial to continue analyzing and monitoring the data, adjusting marketing strategies, along with offering attractive discounts and promoting them effectively and providing a seamless redemption process for drivers will help improve the acceptance rate.

# Link to notebook:

https://github.com/ashwinisanagoudar/coupon-acceptance/blob/main/prompt.ipynb
