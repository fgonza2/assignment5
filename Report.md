## Analysis Report


The dataset provided was analyzed graphically and statistically using Pandas, Seaborn and Plotly Express.

Steps Taken:
 - Loaded the dataset
 - Analyzed the data quality and performed the proper cleaning operations using Pandas
 
 **Types of coupons:**

 Compared the quantity of different types of coupons as seen below.   Coffee House and restaurants are the most popular
![enter image description here](https://github.com/fgonza2/assignment5/blob/main/images/coupon%20bar%20plot.png)

**Overall coupon acceptance**
Around 41% of issued coupons ended up being accepted.   As seen below, the bar, expensive restaurants and coffee house had the highest acceptance rates.
![enter image description here](https://github.com/fgonza2/assignment5/blob/main/images/coupon%20acceptance%20per%20category.png)

**Analysis of the 'Bar' coupons**
I analyzed the customers that visited the bar and here are the findings:
 - 76% acceptance rate for customers that visited the bar more than 3 times before.  This means repeat customers will likely accept the coupons more often
 - For customers 25 years or older and visited more than once a month, the acceptance rate was 69%.     It is a contrast with all other customers that had a low acceptance rate of 27%.   In other words customers that have never been in the bar have less probability to accept the coupon
 - Other cases for customers that had passengers that were not a kid or not widowed also had a 70%+ acceptance rate
 - Main conclusion on the bar coupons is that coupons are very effective for people that have been in the bar previously, as a comparison the acceptance rate for cheap restaurants for people that are also repeat customers and have income less than 50K is 41%, which is significantly lower.   The bar seems to be much more effective as a coupon vs. cheap restaurants.   

**Understanding the Coffee House coupons**
As an additional analysis i looked at a different coupon category and used different graphing techniques to facilitate visualization of categorical multi-variable datasets.    I used sunburst and treemap charts for quick and simpler visualization along with more sophisticated queries and filtering. 
![enter image description here](https://github.com/fgonza2/assignment5/blob/main/images/sunburst%20chart.png)

**Findings and conclusions**
-   86% of the cases for the accepted coupons the passengers were friends or they were alone
-   Of the people that accepted the coupon 64% has been in teh Coffee House at least once
-   80% of the accepted coupons were going the opposite direction
-   Regardless of gender and number of visits most of the drivers that accepted the coupon were going to "No urgent place"

As an additional measure i wanted to have a brief understanding of other aspects such as:
-   Impact of time to get to the promo location
-   Occupation
-   Gender

In this case i used a TreeMap chart
![enter image description here](https://github.com/fgonza2/assignment5/blob/main/images/treemap%202.png)

This type of chart rally helps with visualization of multi-dimensional categorical datasets. We can conclude the following:

-   Most accepted coupons are between 5 and 15 mins driving time
-   The most popular occupations are Unemployed and Student. Being Unemployed more prominent on females and student on males
-   The Gender category is roughly 50/50, so that is likely not a factor

