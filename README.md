
# Project Title
Will a Customer Accept the Coupon?



## OverView
This is In this first practical application assignment of the UC Berkley Professional Certificate in Machine Learning and Artificial Intelligence program. Use visualizations and probability distributions, and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.
 
## Data
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).
detail data is included in the git Repository with Jupyter notebook.
## Goal
Explore the data, use pandas and Python to create statistical summaries demonstrating differences in those who accepted and rejected the coupon. Utilize the Matplotlib and Seaborn libraries to create a visualization using Python.

## Data cleanup
Use pandas liberary to clean up data in the corrsponding features, to ensure the accuracy of the finding.
## Finding
1. Out of different coupons, cheap retaurant, carry out &take away and coffee House have high coupon acceptance in terms of rate and counts. While bar and retaurant(20-50) have lower coupon acceptace in terms of rate and counts.
2. For bar coupon:
    2.1 Drivers who go to bar less than 3 times accept coupon rate is much higher than drivers go to bar 3 or less times in a month.
    2.2 Drivers who is under 30 years old and go to bar more than 1 times per month intent to have higher acceptance of bar coupon .
    2.3 Drivers go to cheap restaurant more than 4 times a month and annual income less than 50K intent to have higher bar coupon acceptance rate.
    2.4 Drivers dont have kid(s) as passenger, and go to bar more than once a month tent to have high coupon acceptance rate. While those who have passenger(s) as kid(s) tend to reject coupon.
3. For coffee house coupon:
    drivers that younger than 41 years old, student, Computer & Mathematical, higher education(some colledge or more), visit coffee house more often, in the morning hours 10AM, intent to accept coffee house coupon more. For drivers never go to coffee house, or some high school education, their coffeehouse coupon acceptance in terms of counts and rate are very low.
   
## Next steps:
1. Explore more the acceptance rate for coffee house coupon, with combination of the features, ie, combine age with income, occupation...etc. 
2. Target the group mentioned above, for distribution of coffeeHouse coupon in counts and accpetance rate.
3. Explore other coupons, ie, takeAway... and target distribution base on the similar analaysis.
   
## Repository 
This Repository includes:
1. jupyter notebook.You can find at https://github.com/xtinbird/coupon-analysis/blob/main/notebook/prompt.ipynb
2. data.You can find at https://github.com/xtinbird/coupon-analysis/blob/main/notebook/data/coupons.csv
3. README.md

Directory & Folder Hierarchy as following:
├── notebook/
|   ├── data/
|   |   └── coupons.csv
|   └── prompt.ipynb
└── README.md

## Environment setup and instructions
git clone < your-repository-url >
cd < your-repository-folder >
git pull origin main
run with Jupyter notebook prompt.ipynb file.
You might need to change the data file diretory in read csv, depends on which directory coupons.csv located.
