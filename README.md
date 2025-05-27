**Marketing Campaign Effectiveness Analyzer**

**Overview**

This project explores sales and marketing data to understand what makes a retail campaign successful. It looks at different types of promotions, market sizes, and store details to figure out which factors actually drive sales — and whether we can predict which customers are likely to respond.

The goal is simple: help marketers focus their efforts where it matters most.

**What This Project Does**
-Cleans and prepares a dataset of 548 marketing records

-Visualizes trends like sales by week, market size, and promotion type

-Builds two machine learning models:

One to predict revenue (using a regression model)

One to predict customer response (using a classification model)

-Looks at which features matter most in each case

-Evaluates how well the models perform on unseen data

**Key Takeaways**
-Promotion_2 stood out as the most effective strategy for boosting revenue

-Large markets consistently performed better than small or medium ones

-Week number and weekly sales were the strongest predictors of whether someone responded to a campaign

-The revenue model explained about 89% of the variation in sales

-The response model hit 100% accuracy on the test data — although the dataset was fairly simple and controlled

**What Was Visualized**
-Sales trends by market and promotion type

-How features like store age and market size relate to revenue

-The importance of different variables in the final models

**Features Used**
-MarketID

-MarketSize

-LocationID

-AgeOfStore

-Promotion type

-Week number

-Weekly sales (in thousands)

**Recommendations**
-Focus future campaigns on Promotion_2, especially in large markets

-Look closely at what’s working in Market 3 — it consistently outperformed others

-Use the classification model to better target likely responders

-Don’t treat all markets the same — tailor campaigns by region and market size

-Keep testing and learning. This model is a great start, but ongoing analysis will help you stay sharp
